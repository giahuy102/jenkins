pipeline {
  agent any
  parameters {
    file 'small'
  }
  stages {
    stage('Example') {
      steps {
        sh 'cat $small'
      }
    }
  }
}