pipeline {
    agent any
    stages{
        stage('Git clone'){
            steps{
                git 'https://github.com/Elilarasu/HelloWorld-Springboot-App.git'
            }
        }
        stage('Creat Dockerimage'){
            steps{
                sh 'docker build -t thetips4you/springboot:latest .'
         
            }
        }
    }
}
