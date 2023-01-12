pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'build no $BUILD_NUMBER of demo $DEMO'
      }
    }

  }
  environment {
    DEMO = '2'
  }
}