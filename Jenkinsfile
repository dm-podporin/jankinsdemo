pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'npm install' // Install Node.js dependencies
                sh 'npm run build' // Build the application
            }
        }
        stage('Test') {
            steps {
                sh 'npm test' // Run the application tests
            }
        }
    }
}