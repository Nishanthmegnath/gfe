pipeline {
    agent any
    stages{
        stage('Git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/Nishanthmegnath/gfe.git'
            }
        }
         stage('Maven unit test'){
            steps{
                sh 'mvn test'
            }
        }
    }
 }
