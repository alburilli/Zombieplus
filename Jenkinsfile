pipeline {
    agent {
        docker { image "alburilli/node-wd"}
    }
    stages {
        stage('Build') {
            steps {
                sh "npm install"
            }
        }
        stage('tests') {
            steps {
                sh "npm run test:ci"
            } 
        }
    }
}