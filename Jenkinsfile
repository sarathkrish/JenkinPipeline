pipeline {
    agent any
    stages {
        stage('Init') {
            steps {
                sh 'whoami'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
