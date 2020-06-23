pipeline {
  agent {
    docker {
      image 'docker:latest'
    }

  }
  stages {
    stage('docker-version') {
      steps {
        tool 'Docker'
        sh 'docker version'
      }
    }
  }
}