pipeline {
    agent {
        docker {
            image 'node:18.18.0-alpine3.18'
            args '-p 3000:3000'
        }
    }
    environment {
        CI = 'true'
    }
    
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
       
    }
}
