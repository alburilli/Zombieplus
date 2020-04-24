pipeline {
    agent any
    stages {
        stage('Build') {
            sh "npm install"
        }
        stage('tests') {
            sh "npm test"
        }
    }
}