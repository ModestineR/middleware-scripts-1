pipeline {
    agent any

    stages{
        stage("creat zip file"){
            steps{
            zip middlewasreScript${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md
            }
        }
    
    } 
}