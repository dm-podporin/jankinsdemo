pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                dir('code') {
                    sh 'npm install'
                }
            }
        }
    }
}