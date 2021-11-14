pipeline {
   agent {
        docker {
          image 'node:15.13-alpine'
        }
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