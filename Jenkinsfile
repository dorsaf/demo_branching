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
        stage('Deploy - Staging') {
             when {
                 branch 'staging'
             }
             steps {
                 echo 'Deploying to Staging from the develop branch.'
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
