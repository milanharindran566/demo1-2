pipeline {
  agent any
  stages {
    stage('Print Message') {
      steps {
        echo 'The build number is $BUILD_NUMBER'
      }
    }

  }
  environment {
    DEMO = '1'
    TEST1 = 'fret'
  }
}