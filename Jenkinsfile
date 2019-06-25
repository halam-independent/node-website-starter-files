pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'make' (1)
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
