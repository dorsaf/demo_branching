pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout...'
            }
        }
        stage('Deploy - Staging') {
             when {
                 branch 'staging'
             }
             steps {
                 echo 'Deploying to Staging from the develop branch.'
             }
        }
    }
}
