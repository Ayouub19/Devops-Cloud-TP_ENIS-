pipeline {
    agent any
    stages {
        stage('Checkout code') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: '534822c0-10f7-4679-a863-da92aba2f9a8', url: 'https://github.com/Ayouub19/Devops-Cloud-TP_ENIS-.git']])
            }
        }
    }
}
