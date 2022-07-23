pipeline {
  agent any
  stages {
    stage('boss2') {
      steps {
        sh 'echo "Test"'
      }
    }

    stage('error') {
      steps {
        dir(path: '..')
      }
    }

  }
}