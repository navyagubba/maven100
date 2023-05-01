
@Library("mylibrary")_
node('built-in')

{
    stage('contdownload')
    {
        cicd.newGit("maven")
    }
    stage('contbuild')
    {
        cicd.newMaven()
    }
}
