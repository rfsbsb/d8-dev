pipeline {
  agent {
    docker {
      image 'php'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'php --version'
        sh 'composer install'
      }
    }
  }
}