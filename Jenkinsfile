
pipeline {
    parameters { booleanParam(name: 'Docker', defaultValue: false, description: 'docker buid')
                 booleanParam(name: 'images', defaultValue: false, description: 'docker buid') 
    }
    
   
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
         stage('dockerimages') {
            steps {
                script{
                    if(params.images == true){
                        sh 'docker images'
                    }
                    
                }
           }
       }
        

  }
}
