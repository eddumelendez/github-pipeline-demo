pipeline {
  agent any
  stages {
    stage('Build') {
      when {
        branch 'develop'
      }
      steps {
        echo 'Building...'
      }
    }
    stage('Test') {
      steps {
        parallel(
          "Test": {
            echo 'Testing...'
            
          },
          "Integration Test": {
            echo 'Running Integration Tests'
            
          }
        )
      }
    }
  }
}