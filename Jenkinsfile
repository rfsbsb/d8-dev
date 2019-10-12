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
        sh 'sudo curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer'
        sh 'composer install'
      }
    }
  }
}