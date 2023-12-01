<<<<<<< HEAD
pipeline {
  agent { label 'linux' }
  tools { maven 'Maven' }
  stages {
    stage('version') {
      steps {
        sh 'pwsh --version'
      }
=======
pipeline{
agent { 
    label 'linux'
}
tools{
    maven 'Maven'
}
stages{
    stage("SCM Checkout"){
        steps{
        git 'https://github.com/cebuanos/jenkins-example-scripts-powershell.git'
        }
>>>>>>> c5af1e2c64b20580781e7c34d76d228e85194cdc
    }
    stage("Maven Build"){
        steps{
            sh 'mvn clean package'
        }
    }
}
