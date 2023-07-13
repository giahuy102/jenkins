pipeline {
  agent any
  parameters {
    file(name: 'file.txt')
  }
  stages {
    stage('Example') {
      steps {
        sh 'cat file.txt'
      }
    }
  }
}