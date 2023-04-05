pipeline {
  agent any {
    stages {
      stage ('Build') {
        steps {
          sh 'npm install -g'
        }
      }
      stage ('Deploy') {
        steps {
          sh 'npm run start'
        }
      }
    }
  }
