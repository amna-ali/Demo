pipeline {
    agent { label 'test-machine2' }

    stages {
        stage('Build') {
            steps {
                sh 'touch /home/jenkins/amna2'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
        input 'Do you approve deployment?'
            steps {
                sh 'cd /home/jenkins/Demo && git pull origin master'
            }
        }
    }
}
