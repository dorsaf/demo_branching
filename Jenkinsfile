pipeline {
    agent any
    stages {
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
