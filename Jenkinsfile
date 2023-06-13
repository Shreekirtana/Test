pipeline {
    agent { label 'slave3' } 
    stages {
        stage('checkout') {
            steps {
                sh 'echo checkout step'
            }
        }
      stage('testing') {
            steps {
                sh 'echo testing step'
            }
        } 
        stage('Develop') {
            steps {
                sh 'echo develop step'
            }
        }
    }
}
