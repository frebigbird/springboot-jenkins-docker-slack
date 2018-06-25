pipeline {
  agent any
  stages {
    stage('fabric') {
      steps {
        sh 'fab -f /tmp/fabfile.py host_type'
      }
    }
    stage('Build') {
      steps {
        sh 'echo Build'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploy'
      }
    }
    stage('Test') {
      steps {
        sh 'echo Test'
      }
    }
    stage('Report') {
      steps {
        sh 'sleep 1'
      }
    }
  }
}
