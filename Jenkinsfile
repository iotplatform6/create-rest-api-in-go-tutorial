pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        tool(name: 'go1.15', type: 'go build')
        sh 'go build -o api'
      }
    }

  }
}