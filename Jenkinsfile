pipeline {
    agent any
    stages {
        stage('Deploy Django App') {
            steps {
                sh 'docker-compose down || true'
                sh 'docker-compose up -d'
            }
        }
    }
}
