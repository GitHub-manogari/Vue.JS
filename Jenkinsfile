pipeline {
  agent {
    docker {
      
      args '-p 5000:5000'
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