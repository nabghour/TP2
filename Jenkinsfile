pipeline {
    agent any

    stages {
        stage('preparation') {
            steps {
                sh 'echo preparation '
                sh 'sleep 5'
            }
        }
        stage('Build') {
            steps {
                sh 'chmod +x TP2/essai.sh'
                sh 'sleep 5'
            }
        }
        stage('RUN') {
            steps {
                sh 'TP2/essai.sh'
                sh 'sleep 5'
            }
        }
    }
}
