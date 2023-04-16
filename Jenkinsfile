pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                dir('code') {
                    sh 'npm install' 
                    sh 'npm build'  
                }
            }
        }
        stage('Test') {
            steps {
                dir('code') {
                    sh 'npm test'
                } 
            }
        }
    }
}