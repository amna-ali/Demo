<<<<<<< HEAD
Jenkinsfile (Declarative Pipeline)
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
            steps {
                echo 'Deploying....'
            }
        }
    }
=======
node {
stage ('Prepare environment') {
sh 'echo "prepration"'
}
stage ('Code analyse') {
sh 'echo "Run some lints"'
}
stage ('Unit test') {
sh 'echo "Tests will back"'
}
stage ('Build') {
sh 'echo "build now"'
}
stage ('Deploy') {
sh 'ssh jenkins@192.168.190.129 "cd Demo && git pull origin master"'
}
>>>>>>> 328363f71958b15fe51296676ab29a530acf5965
}
