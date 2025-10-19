pipeline {
    agent any
    stages {
        stage('install dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') { 
            steps {
                sh 'npm run test' 
            }
        }
    }
}