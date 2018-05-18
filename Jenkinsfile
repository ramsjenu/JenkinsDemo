pipeline {
  agent any
  stages {
    stage('Validate') {
      steps {
        sh 'mvn validate'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn compilet'
      }
    }
    stage('Pack') {
      steps {
        sh 'mvn package'
      }
    }
    stage('Result') {
      steps {
        echo 'Success'
      }
    }
  }
}