pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building'
                npm install node
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}