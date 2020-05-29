pipeline {
  agent none
  stages {
    stage('Job1 ') {
      parallel {
        stage('Job1 ') {
          steps {
            build 'testjob'
          }
        }

        stage('job3') {
          steps {
            build 'testjob3'
          }
        }

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