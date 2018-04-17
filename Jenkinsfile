pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo "hello ${MY_NAME}!"
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}