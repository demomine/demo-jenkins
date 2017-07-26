pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        parallel(
          "step1": {
            echo 'hello'
            
          },
          "step2": {
            echo 'world'
            echo 'yes'
            echo 'aaa'
            
          }
        )
      }
    }
    stage('step1.1') {
      steps {
        parallel(
          "step1.1": {
            echo 'step11'
            
          },
          "step1.2": {
            echo 'step1.2'
            
          }
        )
      }
    }
  }
}