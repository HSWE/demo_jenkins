pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo 'hello world'
            }
        }
        stage('tooling') {
            steps {
                sh '''
                  docker version
                  docker info
                  docker compose version
                '''
            }
        }
    }
}
