pipeline {
  agent any
  stages {
    stage('Get container log from Kubernetes') {
      steps {
        containerLog 'container'
      }
    }
  }
}