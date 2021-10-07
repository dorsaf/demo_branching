pipeline {
    agent any
    stages {
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
