pipeline {
  agent {
    docker {
      image 'node:10.8.0-alpine'
      args '-p 3000:3000 '
    }
    
  }
  stages {
    stage('') {
      steps {
        sh 'npm install'
      }
    }
  }
}
