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
        sh 'wget https://raw.githubusercontent.com/composer/getcomposer.org/76a7060ccb93902cd7576b67264ad91c8a2700e2/web/installer -O - -q | php -- --quiet'
        sh 'composer install'
      }
    }
  }
}