def username = 'Jenkins'

pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('hello World') {
            steps {
                echo "I said, Hello Mr. ${username}"
            }
        }
        stage('Powershell Hello World'){
            steps {
                sh "hello.ps1"
            }
        }
           
    }
}