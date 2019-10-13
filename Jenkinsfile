pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
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