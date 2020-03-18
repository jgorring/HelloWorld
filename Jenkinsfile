pipeline {
    agent {
        docker { image 'microsoft/azure-documentdb-emulator:latest' }
    }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
