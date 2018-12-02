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
    stage('Do') {
      steps {
        sh '''pwd
java -version'''
      }
    }
  }
}