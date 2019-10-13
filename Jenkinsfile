pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('build') {
      agent any
      steps {
        echo 'Let\'s GO'
        sh 'php --version'
        sh 'composer install'
      }
    }
  }
}