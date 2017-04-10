pipeline {
  agent any
  stages {
    stage('puk-puk') {
      steps {
        sh 'ping -c 10 ya.ru'
      }
    }
    stage('error') {
      steps {
        sh 'traceroute google.com'
      }
    }
  }
}