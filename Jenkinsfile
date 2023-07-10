pipeline {
  agent any
  stages {
    stage('Test') {
      agent any
      steps {
        sh 'pwd'
      }
    }

    stage('Build') {
      steps {
        sh 'echo \'build\''
      }
    }

    stage('Done') {
      steps {
        sh 'echo \'done\''
      }
    }

  }
}