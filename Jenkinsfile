pipeline {
  agent {
    docker {
      image 'linode/lamp'
    }

  }
  stages {
    stage('New build') {
      steps {
        sh 'php -v'
        sh '''sudo apt-get install bash coreutils git make mercurial openssh-client patch 
    unzip 
    zip'''
      }
    }
  }
}