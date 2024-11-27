pipeline {
    agent {
        docker { image 'openjdk:17-jdk-alpine' }
    }

    stages {
        stage('Build') {
            steps {
                sh 'java --version'
            }
        }
    }
}
