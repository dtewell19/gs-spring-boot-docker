pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'openjdk:8-jre-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh '''cd complete/
'''
      }
    }
  }
}