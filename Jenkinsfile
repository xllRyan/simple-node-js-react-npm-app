pipeline {
    agent {
        docker {
            
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
