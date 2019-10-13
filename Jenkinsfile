pipeline {
  agent {
    docker {
      image 'php'
    }

  }
  stages {
    stage('New build') {
      steps {
        sh 'php -v'
      }
    }
  }
}