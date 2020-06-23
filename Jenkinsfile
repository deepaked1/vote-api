pipeline{
agent any
def dockerHome
	stages{
 		stage('Prep'){
  			agent {
    				docker {
      					image 'docker:latest'									}
			}
 		}
	}
}