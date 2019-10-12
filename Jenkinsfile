pipeline {
  agent any
  stages {
    stage('Install dependencies') {
      steps {
        echo 'Installing dependencies'
        sh 'sudo apt-get update && apt-get upgrade'
        sh 'sudo apt-get install curl php-cli php-mbstring git unzip '
      }
    }
  }
}