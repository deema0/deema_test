pipeline {
  agent any
  stages {
    stage('puk-puk') {
      steps {
        sh 'ping -c 10 ya.ru'
      }
    }
    stage('sleep') {
      steps {
        sleep 3
      }
    }
    stage('') {
      steps {
        sh 'traceroute google.com'
      }
    }
  }
}