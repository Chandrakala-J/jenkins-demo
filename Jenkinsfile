pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Chandrakala-J/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy step placeholder'
            }
        }
    }
}
