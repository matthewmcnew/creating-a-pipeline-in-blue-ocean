pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }
    
  }
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sleep 10
          }
        }
        stage('') {
          steps {
            sleep 20
          }
        }
      }
    }
    stage('') {
      steps {
        input 'Hello'
      }
    }
  }
}