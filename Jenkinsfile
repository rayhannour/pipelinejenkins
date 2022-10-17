pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'docker build . -t 090380/eureka-services-1:latest'
      }
    }

  }
}