
pipeline {
    parameters { booleanParam(name: 'Docker', defaultValue: true, description: 'docker buid') }
    agent any
    stages {
         stage('docker build') {
            steps {
                script{
                    if(params.Docker == true){
                        sh 'docker build -t chandu .'
                    }
                    
                }
           }
       }

  }
}
