pipeline {
  agent any
  stages {
    stage('Selenium Chrome') {
      steps {
        parallel(
          "Selenium Chrome": {
            bat '.\\test_chrome.bat'
            
          },
          "Selenium Internet Explorer": {
            bat 'test_iexplorer.bat'
            
          }
        )
      }
    }
  }
}