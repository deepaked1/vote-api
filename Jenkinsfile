node{
  def dockerHome
  dockerHome = tool 'Docker'
  agent {
    docker {
      image 'docker:latest'
    }

  }
    stage('docker-version') {
      withEnv(["DOCKER_HOME=$dockerHome"]) {
	      sh '$DOCKER_HOME/bin/docker version'
      }
    }
}