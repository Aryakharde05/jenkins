pipeline {
    agent any

    stages {
         stage('Clone') {
            steps {
                git branch: 'main', credentialsId: '7d35767c-ba82-4a77-bf46-d3a8aa5104fd', url: 'https://github.com/Aryakharde05/jenkins.git'
              
            }
        }
        
        stage('Compile') {
            steps {
                bat 'javac HelloWorld.java'
              
            }
        }
        stage('Run'){
         steps{
           bat 'java HelloWorld'
         }
      }
    }
}
