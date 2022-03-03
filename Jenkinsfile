
pipeline {
  agent {
   any
  }
  
  options {
  
  }
 

  stages {

	stage('test') {
      when {
        branch "master"
      }
      steps {
        sh "ola ke ase jenkins"
      }
      post {
        success {
          sh "weeee"
        }
        failure {
          sh "buuuuh"
        }
      }
    } //stage    
  } //stages
} //pipeline
