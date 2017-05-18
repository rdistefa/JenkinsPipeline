pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh /var/jenkins_home/scripts/myFirstScript.sh'
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
}