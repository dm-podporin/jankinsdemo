pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'cd ./code && npm install' 
                sh 'npm run build' 
            }
        }
        stage('Test') {
            steps {
                sh 'npm test' 
            }
        }
    }
}