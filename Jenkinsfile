pipeline {
  agent none
  stages {
    stage('dev-env') {
      steps {
        build 'dev-sample-job'
      }
    }
    stage('test-env') {
      steps {
        build 'test-sample-job'
      }
    }
  }
}