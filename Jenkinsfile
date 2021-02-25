pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        sh 'go build -o api'
      }
    }

  }
}