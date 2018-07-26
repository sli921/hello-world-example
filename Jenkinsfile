pipeline {
  agent {
      docker { image 'slave', args '--volumes-from jenkins'}
  }
  stages {
    stage('Build') {
      steps {
        sh 'ls -al'
      }
    }
  }
}
