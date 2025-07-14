pipeline {
  agent any
  stages {
    stage('Print Message') {
      steps {
        sh 'echo "The build number is $BUILD_NUMBER and this is demo $DEMO by your $TEST1"'
      }
    }

  }
  environment {
    DEMO = '1'
    TEST1 = 'fret'
  }
}