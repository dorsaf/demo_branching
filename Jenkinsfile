pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout...'
            }
        }
        stage('Deploy - Development') {
             when {
                 branch 'develop'
             }
             steps {
                 echo 'Deploying to dev from the develop branch.'
             }
        }
    }
}
