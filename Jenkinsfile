pipeline{
	node{
		def dockerHome
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