pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('helloworld') {
      steps {
        sh 'python3 helloword.py'
      }
    }
  }
}