pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                git 'https://github.com/sasan07/Jenkinsdocker.git'
            }
        }
        
        stage('maven build'){
            steps{
                sh 'mvn package'
            }
        }
        stage('Create Dockerimage'){
            steps{
                sh 'docker build -t Hello Master, Welcome to Jenkins!!
All/springboot:latest .'
            }
        }
        
    }
}
