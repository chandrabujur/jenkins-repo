pipeline{
    agent any
    stages{
        stage("welcome"){
            steps{
                git branch: 'main', url: 'https://github.com/chandrabujur/jenkins-repo'
            }
        }
    }
}