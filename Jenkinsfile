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
        input {
                message "Should we continue?"
                ok "Yes, we should."
                submitter "alice,bob"
                parameters {
                    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                }
            }
            steps {
                sh 'cd /home/jenkins/Demo && git pull origin master'
            }
        }
    }
}
