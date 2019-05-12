pipeline {
  agent { dockerfile true }
  stages {
    stage('Run things') {
      steps {
        sh 'docker build . -t slimmy1801/docker-example'
        sh 'docker run slimmy1801/docker-example'
      }
    }
  }     
}