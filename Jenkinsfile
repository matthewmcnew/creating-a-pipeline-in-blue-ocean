pipeline {
  agent none
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sleep 10
          }
        }
        stage('error') {
          steps {
            sleep 20
          }
        }
      }
    }
    stage('error') {
      steps {
        input 'Hello'
      }
    }
  }
}