pipeline {
  agent any
  
  tools {nodejs "node"}
    
  stages {
    stage('Run things') {
      steps {
        sh 'npm install'
        sh 'npm run build'
      }
    }
  }     
}