pipeline {
    agent {
        label '!Linux'
    }

    environment {
        DOCKER_HOME = tool 'Docker'
        PATH = $PATH:$DOCKER_HOME/bin
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