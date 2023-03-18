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
                sh 'docker images > images.txt'
                archiveArtifacts artifacts: 'images.txt'


            }

        }
    }
}