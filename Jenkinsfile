pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'cut -d: -f3 /etc/passwd > /tmp/user'
      }
    }

  }
}