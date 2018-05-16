pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('error') {
      steps {
        echo 'Hello'
      }
    }
  }
  environment {
    test = '1'
  }
}