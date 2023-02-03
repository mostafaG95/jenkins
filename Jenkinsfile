pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/mostafaG95/jenkins/blob/main/Jenkinsfile'

                // Run Maven on a Unix agent.
                sh "ls"

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }

            }
        }
    }
