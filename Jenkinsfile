parameters { booleanParam(name: 'Docker', defaultValue: false, description: 'docker buid') }
pipeline {
    agent any
    stages {
         stage('docker build') {
            steps {
                script{
                    if(params.Docker=='true'){
                        sh 'docker build -t chandu .'
                    }
                }
           }
       }

  }
}
