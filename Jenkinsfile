pipeline {
  agent {
    docker {
      image 'go'
    }

  }
  stages {
    stage('build') {
      agent {
        docker {
          image 'golang'
        }

      }
      steps {
        sh 'go build -o api'
      }
    }

  }
}