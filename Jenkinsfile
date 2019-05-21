pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'alpine:3.7'
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