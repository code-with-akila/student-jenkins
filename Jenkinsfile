pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking Source Code'
            }
        }

        stage('Build') {
            steps {
                sh 'pwd'
                sh 'ls -ltr'
            }
        }

        stage('Read Student File') {
            steps {
                sh 'cat student.txt'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment Successful'
            }
        }
    }
}
