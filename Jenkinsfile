ipeline {
    agent any
    stages{
        stage('Git clone'){
            steps{
                git 'https://github.com/Elilarasu/HelloWorld-Springboot-App.git'
            }
        }
        stage('Maven build'){
            steps{
                sh 'mvn package'
            }
        } 
        
    }
    
}   
       

