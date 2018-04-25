pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:9.11'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}