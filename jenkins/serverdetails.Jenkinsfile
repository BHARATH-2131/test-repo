pipeline {
    agent any
    stages {
        stage('first build') {
            steps {
                sh 'echo build is success'
            }
        }
        stage('second build') {
            steps {
                sh 'uptime'
            }
        }
        stage('third build') {
            steps {
                sh '''
                    hostname
                    df -h
                '''
            }
        }
    }
}
