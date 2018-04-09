pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'docker run -p 8080:8080 -t springio/gs-spring-boot-docker'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

