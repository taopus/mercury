pipeline {
  agent any
  stages {
    stage('Prepare') {
      steps {
        timestamps() {
          echo 'Started with ..'
        }

        echo 'Build started'
      }
    }
    stage('Random') {
      steps {
        sh '''pwd
java -version'''
      }
    }
  }
}