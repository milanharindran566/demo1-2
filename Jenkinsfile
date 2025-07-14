pipeline {
  agent any
  stages {
    stage('Print Message') {
      steps {
        echo 'This is build number $BUILD_NUMBER of demo $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}