pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'javac HelloWorld.java'
              
            }
        }
        stages('Run'){
         steps{
           bat 'java HelloWorld'
         }
      }
    }
}
