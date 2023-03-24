
pipeline {
    parameters { booleanParam(name: 'Docker', defaultValue: false, description: 'docker buid') }
    agent any
    stages {
         stage('docker build') {
            steps {
                script{
                    
                        sh 'docker build -t chandu .'
                    
                }
           }
       }

  }
}
