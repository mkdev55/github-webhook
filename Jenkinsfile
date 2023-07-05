pipeline {
    agent any
    stages {
        stage('Test') {
            stage {
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
