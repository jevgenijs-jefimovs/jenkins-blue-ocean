pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('error') {
          steps {
            sh 'echo "Test"'
          }
        }

        stage('boss') {
          steps {
            echo 'Test me'
          }
        }

      }
    }

    stage('') {
      steps {
        dir(path: '..')
      }
    }

  }
}