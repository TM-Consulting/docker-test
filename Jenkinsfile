pipeline {
    agent any
    tools {nodejs "nodejs"}
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