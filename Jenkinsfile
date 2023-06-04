pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                sh 'rm -rf *'
                sh 'git clone https://github.com/nabghour/TP2.git'
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
