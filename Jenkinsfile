pipeline {
    agent {
        label '!Linux'
    }

    environment {
        DOCKER_HOME = tool 'Docker'
    }

    stages {

        stage('Prep') {
            steps {
                sh 'export PATH=${PATH}:${DOCKER_HOME}/bin'
            }
        }
        stage('Echo') {
            steps {
		echo "PATH is ${PATH}"
            }
        }
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