pipeline {
  agent any
  stages {
    stage('build Saleor') {
      steps {
        sh '''docker-compose build
docker-compose up'''
      }
    }

    stage('build Dashboard') {
      steps {
        sh 'echo "yes"'
      }
    }

    stage('build StoreFront') {
      steps {
        sh 'echo "build storefront"'
      }
    }

  }
}