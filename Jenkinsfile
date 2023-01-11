pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Build step modified"'
            }
        }
        stage('Test') {
            steps {
              sh 'echo "Test step"'
            }
        }
        stage('Deliver') {
            steps {
                sh 'echo "Deliver step"'
            }
        }
    }
}