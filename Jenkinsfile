pipeline {
    agent {
        label '!Linux'
    }

    environment {
        DOCKER_HOME = tool 'Docker'
    }

    stages {

        stage('Build') {
		agent {
		       	docker { image 'docker' }
		}
            steps {
                echo "DOCKER_HOME  is ${DOCKER_HOME}"
                
            }
        }
    }
}