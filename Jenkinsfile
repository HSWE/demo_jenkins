pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo 'hello world'
            }
        }
        stage('Start containers') {
            steps {
                sh 'docker compose -f docker-compose.prod.yml up -d'
            }
        }
    }
}
