pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ssh -T jenkins@192.168.190.129 '
                sh 'touch /home/jenkins/amna'
             
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
