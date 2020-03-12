pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''id=2
echo $id'''
      }
    }

  }
  environment {
    id = '1'
  }
}