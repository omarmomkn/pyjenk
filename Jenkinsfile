pipeline {
    agent { label 'docker' }
    stages {
        stage('python test') {
             agent {
        docker {
          label 'docker'
          image 'python:3.10-alpine'
            steps {
                sh 'python --version'
                    }
                }
            }
        }
    }
}
