pipeline {
    agent {
        docker { image 'microsoft/azure-documentdb-emulator:latest' }
    }
    stages {
        stage('build') {
            steps {
                sh 'docker run --name azure-cosmosdb-emulator --memory 2GB'
            }
        }
    }
}
