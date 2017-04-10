pipeline {
  agent any
  stages {
    stage('puk-puk') {
      steps {
        parallel(
          "puk-puk": {
            sh 'ping -c 10 ya.ru'
            
          },
          "": {
            sh 'ping -c 5 yahoo.com'
            
          }
        )
      }
    }
    stage('error') {
      steps {
        sh 'traceroute google.com'
      }
    }
  }
}