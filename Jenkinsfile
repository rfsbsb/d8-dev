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
        sh 'echo  "Starting building"'
        sh 'php --version'
        sh 'composer install'
      }
    }
  }
}