pipeline{
  agent {
    docker {
      image 'docker:latest'
    }

  }
  stages{
    stage('docker-version') {
      withEnv(["DOCKER_HOME=$dockerHome"]) {
	      sh '$DOCKER_HOME/bin/docker version'
      }
    }
  }
}