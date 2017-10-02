pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        parallel(
          "error": {
            echo 'test'
            
          },
          "": {
            git 'https://github.com/mwerner1984/locke.git'
            
          }
        )
      }
    }
  }
}