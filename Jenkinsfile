pipeline {
  agent any

  stages {
    stage('build') {
      steps {
        sh 'echo build'
      }
    }
    stage('test') {
      steps {
        sh 'echo test'
        exit 1
      }
    }
    stage('deploy') {
      steps {
      	sh 'echo deploy'
      }
    }
  }
}
