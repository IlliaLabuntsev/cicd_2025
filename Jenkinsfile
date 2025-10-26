pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'echo Build step executed'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo Deploy complete'
            }
        }
    }
}