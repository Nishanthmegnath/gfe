pipeline {
    agent any
    stages{
        stage('Git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/Nishanthmegnath/gfe.git'
            }
        }
         stage('UNIT Testing'){
            steps{
                sh 'mvn test'
                set +e  
            }
        }
    }
 }
