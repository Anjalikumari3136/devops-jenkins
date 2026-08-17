pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building website...'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing website...'
                sh 'test -f index.html'
                sh 'test -f index.css'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage'
            }
        }
    }
}