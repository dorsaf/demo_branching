pipeline {
    agent any
    stages {
        stage('Deploy - Development') {
             when {
                 branch 'develop'
             }
             steps {
                 sh '''
                    sudo su jenkins
                    ls -l
                 '''
                 echo 'Deploying to dev from the develop branch.'
             }
        }
    }
}
