pipeline {
  agent {
    docker {
      image 'drupal'
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