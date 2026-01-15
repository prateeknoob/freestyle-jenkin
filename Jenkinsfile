pipeline {
    agent {
        label 'dev'
    }

    stages {
        stage('Create Folders') {
            steps {
                sh '''
                    mkdir -p a b
                    ls -l
                '''
            }
        }
    }
}
