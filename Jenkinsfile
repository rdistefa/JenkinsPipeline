pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh build.sh'
      }
    }
    stage('Test') {
      steps {
        echo 'Hello world'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy completed'
      }
    }
  }
}