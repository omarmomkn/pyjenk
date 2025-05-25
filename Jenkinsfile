pipeline {
    agent { label 'docker' }
              image 'python:3.10-alpine'

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
