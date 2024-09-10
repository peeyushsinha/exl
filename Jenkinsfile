pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('welcome') {
      steps {
        sh 'python3 welcome.py'
      }
    }
  }
}