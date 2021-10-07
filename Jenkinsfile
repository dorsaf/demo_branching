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
                    ssh dorsafd@192.168.112.1
                 '''
                 echo 'Deploying to dev from the develop branch.'
             }
        }
    }
}
