pipeline {
  agent {
      docker { image 'slave' }
  }
  stages {
    stage('Build') {
      steps {
        sh 'ls -al'
      }
    }
  }
}
