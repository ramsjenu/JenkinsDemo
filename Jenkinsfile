pipeline {
  agent none
  stages {
    stage('Validate') {
      steps {
        sh 'mvn validate'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn compile'
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