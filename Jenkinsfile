pipeline {
  agent any
  stages {
    stage('Install dependencies') {
      steps {
        echo 'Installing dependencies'
        sh 'apt-get update && apt-get upgrade'
        sh 'apt-get install curl php-cli php-mbstring git unzip '
      }
    }
  }
}