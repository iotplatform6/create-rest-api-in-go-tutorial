pipeline {
  agent {
    docker {
      image 'golang'
      args '-p 3000:10000'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'go build -o api'
      }
    }

  }
}