parameters { booleanParam(name: 'Docker', defaultValue: false, description: 'docker buid') }
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
            

        stage('docker build') {
            steps {
                sh 'docker build -t chandu .'
                


            }

        } 
   /*       stage('checking docker images') {

               steps {
                  sh 'docker images > images.txt'
                  archiveArtifacts artifacts: 'images.txt'
              }
            } */


           
    

    }
}