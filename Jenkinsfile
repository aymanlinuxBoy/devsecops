pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo "Hello world" '
          }
        }

        stage('') {
          steps {
            echo 'Build done succes'
          }
        }

      }
    }

    stage('tst stages') {
      parallel {
        stage('tst stages') {
          steps {
            sh 'echo "test done" '
          }
        }

        stage('test 1') {
          steps {
            echo 'running test 1'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'done deployment'
      }
    }

  }
}