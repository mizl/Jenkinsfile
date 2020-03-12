pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'echo 1'
        build 'test'
      }
    }

  }
  environment {
    id = '1'
  }
}