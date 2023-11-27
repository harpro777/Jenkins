pipeline {
    agent any

    environment {
        VER = "${sh(script:'echo 1.23', returnStdout: true).trim()}"
        BUILD_VERSION = "${env.VER}"
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
                sh 'date'
            }
        }
    }
}
