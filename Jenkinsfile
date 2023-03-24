
pipeline {
    parameters  { booleanParam(name: 'floder', defaultValue: false, description: 'creating floder') }
    agent any
    stages {
        stage('creating floder') {
           steps {
              script{
                  if(params.floder == true){
                      sh 'mkdir chandu'
                  }
              }     
           }
        }
    }
}