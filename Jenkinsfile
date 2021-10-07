pipeline {
    agent any
    stages {
        stage('Deploy - Development') {
             when {
                 branch 'develop'
             }
             steps {
                 sh '''
                    ssh jenkins@192.168.1.35 ls -l
                 '''
                 echo 'Deploying to dev from the develop branch.'
             }
        }
    }
}
