pipeline {
    agent any
    stages {
        stage('Deploy - Development') {
             when {
                 branch 'develop'
             }
             steps {
                 sh '''
                    ssh vagrant@127.0.0.1 -p 2201 ls -l /bin
                 '''
                 echo 'Deploying to dev from the develop branch.'
             }
        }
    }
}
