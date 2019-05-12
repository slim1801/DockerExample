pipeline {
  agent any
  
  tools {nodejs "node"}
    
  stages {
    stage('Run things') {
      steps {
        sh 'docker build -t slimmy1801/docker-example'
        sh 'docker run slimmy1801/docker-example'
      }
    }
  }     
}