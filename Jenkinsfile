pipeline {
    agent {
        label '!Linux'
    }

    environment {
        DOCKER_HOME = tool 'Docker'
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