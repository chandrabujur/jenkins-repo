pipeline{
    agent any
    stages{
        stage("git checkout"){
            steps{
                git branch: 'main', url: 'https://github.com/chandrabujur/jenkins-repo'
            }
        }
        stage("build docker image"){
          steps{
            sh "docker build -t chandu ."
          }  
        }
        }
    }
}