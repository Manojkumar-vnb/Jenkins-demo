pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage running'
            }
        }
        stage('Test') {
            steps {
                echo 'Test stage running'
            }
        }
    }

    post {
        success {
            echo 'BUILD SUCCESSFUL'
        }
        failure {
            echo 'BUILD FAILED'
        }
    }
}
