pipeline {
    agent any
    stages {
        stage('Test') {
            agent {
                any{
                    image "docker:dind"
                }
            }
            steps {
                sh 'docker -v'
            }
        }
    }
}
