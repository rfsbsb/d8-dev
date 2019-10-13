pipeline {
  agent {
    docker {
      image 'drud/ddev-webserver'
    }

  }
  stages {
    stage('build') {
      agent any
      steps {
        echo 'New image'
        sh 'php --version'
        sh 'composer install'
      }
    }
  }
}