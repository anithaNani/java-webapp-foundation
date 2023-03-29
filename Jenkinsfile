pipeline{
    agent any
    tools {
       maven 'maven'
    }
    stages{
        stage("Git Checkout"){
            steps{
                git credentialsId: 'javahome', url: 'https://github.com/anithaNani/java-webapp-foundation.git'
            }
        }
    }
