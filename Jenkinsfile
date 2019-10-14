pipeline {
  agent {
    docker {
      image 'php'
    }

  }
  stages {
    stage('New build') {
      steps {
        sh 'php -v'
        sh '''apt-get install bash coreutils git make mercurial openssh-client patch 
    unzip 
    zip'''
      }
    }
  }
}