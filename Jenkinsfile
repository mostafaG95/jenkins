pipeline {
    agent any
    stages {
        stage('Clone repository') {
            steps {
                git 'https://github.com/mostafaG95/jenkins.git'
            }
        }
        stage('List files') {
            steps {
                sh 'ls'
            }
        }
    }
}
