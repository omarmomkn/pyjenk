pipeline {
    agent { docker { image 'python:latest' } }
    stages {
        stage('pull') {
            steps {
                sh 'python --version'
            }
        }
    }
}
