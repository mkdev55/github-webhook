// Declarative //
pipeline {
    agent any
    stages {
        stage('Build') {
            agent {
                docker {
                    image "docker:dind"
                }
            }
            steps {
                docker -v
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
