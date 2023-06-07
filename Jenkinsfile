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
                sh 'chmod +x essai.sh'
                sh 'sleep 5'
            }
        }
        stage('RUN') {
            steps {
                sh './essai.sh'
                sh 'sleep 5'
            }
        }
    }
}
