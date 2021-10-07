pipeline {
    agent any
    stages {
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
