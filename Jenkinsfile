pipeline {
   agent any
   environment {
     SERVICE_NAME = "testing"
   }
   stages {
      stage('Preparation') {
         steps {
            sh "echo preparation started"
            sh "echo preparation completed"
         }
      }
      stage('Build and Push Image') {
         steps {
           sh './test.sh'
         }
      }
   }
}