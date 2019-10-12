pipeline {
  agent any
  stages {
    stage('Install dependencies') {
      steps {
        echo 'Installing dependencies'
        sh 'sudo -S apt-get update && apt-get upgrade'
        sh 'sudo -S apt-get install curl php-cli php-mbstring git unzip '
      }
    }
  }
}