pipeline {
    agent {
        label 'siva'
    }

    stages {
        stage('NodeJS') {
            steps {
                sh """
                node -v
                npm -v
                """
            }
        }
        stage('docker version') {
            steps{
             sh 'docker version'   
            }
        }
    }
}
