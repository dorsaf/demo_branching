pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout...'
            }
        }
        stage('Deploy - Production') {
             when {
                 branch 'main'
             }
             steps {
                 echo 'Deploying to production from the main branch.'
             }
        }
    }
}
