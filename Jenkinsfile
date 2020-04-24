pipeline {
    agent {
        docker {
             image "alburilli/node-wd"
             args "--network=skynet"
             }
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