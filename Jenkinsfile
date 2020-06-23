pipeline {
  agent {
    docker {
      image 'docker:latest'
    }

  }
  stages {
    stage('docker-version') {
      steps {
        sh 'docker version'
        tool 'Docker'
      }
    }
  }
}