pipeline{
    agent any
    stages{     
        stage("build docker image"){
          steps{
            sh "sudo su; docker build -t chandu ."
          }  
        }
    }
}