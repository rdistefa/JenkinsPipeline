pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'riccardoJob'
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
  environment {
    IMAGE_TAG = 'riccardo/bwce:latestv2'
  }
}