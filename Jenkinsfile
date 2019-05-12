pipeline {
  agent { dockerfile true }
  tools { docker "docker" }
  stages {
    stage('Run things') {
      steps {
          sh 'node --version'
      }
    }
  }     
}