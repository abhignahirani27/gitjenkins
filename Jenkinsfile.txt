pipeline{
    agent any
    stages{
        stage("Message"){
            steps{
                git 'git@github.com:abhignahirani27/gitjenkins.git'
            }
        }
    }
}