pipeline {
    agent any
    stages {
        stage('build') {
            steps{
                bat 'npm install'
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