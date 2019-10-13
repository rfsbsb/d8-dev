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
        sh 'php --version'
        sh 'composer install'
      }
    }
  }
}