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
        echo 'New image'
        sh 'php --version'
        sh 'composer install'
      }
    }
  }
}