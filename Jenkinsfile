pipeline {
  agent none
  stages {
    stage('Job1 ') {
      steps {
        build 'testjob'
      }
    }

    stage('job2') {
      steps {
        build 'testjob2'
      }
    }

  }
  environment {
    test = 'test'
  }
}