pipeline {
  agent any
  tools {
       maven 'Maven 3.6'
      }
  stages {
    stage ('Build') {
          steps{
                sh script: 'mvn clean package'
                }
          }
        }
   }
