pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ssh jenkins@192.168.190.129'
                sh "touch amna"
             
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
