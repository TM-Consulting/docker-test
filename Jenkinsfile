pipeline {
    agent {
        docker {
            image 'node:15.13-alpine'
            args '-p 3000:3000'
        }
    }
    environment {
        CI = 'true' 
    }
    stages {
        stage('build') {
            steps{
                sh 'npm install'
            }
        }

        stage('test') {
            steps{
                echo "testing the application"
            }
        }

        stage('deploy') {
            steps{
                echo "deploting the application"
            }
        }
    }
}