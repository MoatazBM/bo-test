pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'test.'
        echo 'another test.'
      }
    }
    stage('build') {
      steps {
        build 'build'
      }
    }
  }
}