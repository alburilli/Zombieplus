pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "npm install"
            }
        }
        stage('tests') {
            steps {
                sh "npm test"
            } 
        }
    }
}