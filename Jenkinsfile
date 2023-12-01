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
    }
    stage("Maven Build"){
        steps{
            sh 'mvn clean package'
        }
    }
}
