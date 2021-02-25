pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        tool(name: 'go1.14', type: 'go build')
        sh 'go build'
      }
    }

  }
}