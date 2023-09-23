pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Start Building'
      }
    }

    stage('Test 1') {
      parallel {
        stage('Test 1') {
          steps {
            echo 'Start Test 1'
          }
        }

        stage('Test 2') {
          steps {
            echo 'start Test 2'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Start deploy'
      }
    }

  }
}