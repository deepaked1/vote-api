pipeline{
    environment {
        DOCKER_HOME = tool 'Docker'
    }
	stages{
 		stage('Prep'){
  			agent {
    				docker {
      					image 'docker:latest'									}
			}
 		}
	}
}