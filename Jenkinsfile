pipeline {
    agent {
        label '!Linux'
    }

    environment {
        DOCKER_HOME = tool 'DOCKER'
    }

    stages {
        stage('Build') {
            steps {
                echo "DOCKER_HOME  is ${DOCKER_HOME}"
                sh 'printenv'
            }
        }
    }
}