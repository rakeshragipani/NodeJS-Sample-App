pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/rakeshragipani/NodeJS-Sample-App.git'
            }
         }
    stage('Build') {
      steps {
        sh 'npm config ls'
        sh 'npm pack'
              }
      }
        }
       }
