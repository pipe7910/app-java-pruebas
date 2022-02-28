pipeline {
  agent any
  stages {
    stage('Package') {
      steps {
        build 'job/final/job1'
      }
    }

    stage('deploy qa') {
      steps {
        build 'deploy qa'
      }
    }

  }
}