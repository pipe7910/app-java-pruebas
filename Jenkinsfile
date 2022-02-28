pipeline {
  agent any
  stages {
    stage('Package') {
      steps {
        build 'job1'
      }
    }

    stage('deploy qa') {
      steps {
        build 'deploy qa'
      }
    }

  }
}