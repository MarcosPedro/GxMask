pipeline {
  agent any
  stages {
    stage('teste estagio') {
      steps {
        timeout(time: 2, activity: true)
      }
    }
    stage('msg') {
      steps {
        echo 'teste de mensagem'
      }
    }
  }
  environment {
    gx = '1'
  }
}