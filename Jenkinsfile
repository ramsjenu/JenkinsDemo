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
  }
}