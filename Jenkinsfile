pipeline {
  agent any
  stages {
    node('jenkins-dind') { 
      stage ('test') {
        container('dind') {
          sh 'echo hello world'
        }
      }
    }
  }
}
