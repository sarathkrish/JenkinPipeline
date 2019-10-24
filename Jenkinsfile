pipeline {
    agent any
    stages {
        stage('Init') {
            steps {
                sh 'docker ps'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
