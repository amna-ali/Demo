pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                sh "ant -f build.xml -v"
            }
        }
        stage('Test') { 
              steps {
        echo 'Awesome Test!'
      }
 
    }
    stage('Deploy') { 
      steps {
        echo 'Awesome Prod!'
      }
 
    }

            }
        }
