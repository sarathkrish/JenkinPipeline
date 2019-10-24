pipeline {
    agent any
    stages {
        stage('Init') {
            steps {
                sh 'sudo yum -y install docker'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
