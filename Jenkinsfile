pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        tool(name: 'go1.15', type: 'go1.15')
        sh 'go build -o api'
      }
    }

  }
}