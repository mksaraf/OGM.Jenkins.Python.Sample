pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python3 hello.py'
      }
    stage('fun3') {
      steps {
        sh 'python3 -c import hello; hello.my_function()'
      }
    }
  }
}
