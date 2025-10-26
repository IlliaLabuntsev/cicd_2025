pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
                bat 'echo Build step executed'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                bat 'echo Deploy complete'
            }
        }
    }
}