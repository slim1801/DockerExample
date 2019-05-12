pipeline {
  agent { dockerfile true }
  stages {
    stage('Initialize'){
        steps {
            def dockerHome = tool 'myDocker'
            env.PATH = "${dockerHome}/bin:${env.PATH}"
        }
    }
    stage('Run things') {
      steps {
          sh 'node --version'
      }
    }
  }     
}