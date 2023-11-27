pipeline {
    agent any

    environment {
        BUILD_VERSION = 1.0
    }
    tools {
        
    }

    stages {
        stage('Clone') {
            steps {
                echo "Cloning Hello World ${BUILD_VERSION}"
                sh 'hostname'
            }
        }

        stage('Build') {
            steps {
                echo "Building Hello World ${BUILD_VERSION}"
                sh 'hostname'
                sh 'date'
            }
        }

        stage('Test') {
            steps {
                echo "Test Hello World ${BUILD_VERSION}"
                sh 'hostname'
            }
        }
    }
}
