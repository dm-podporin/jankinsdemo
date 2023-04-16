pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/username/repo.git'
            }
        }
        
        stage('Build') {
            steps {
                sh 'make'
            }
        }
    }
}