pipeline {
  agent any
  parameters {
    base64File 'small'
  }
  stages {
    stage('Example') {
      steps {
        withFileParameter('small') {
          sh 'cat $small'
        }
      }
    }
  }
}