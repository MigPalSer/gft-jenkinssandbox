
pipeline {
  agent any

  stages {

	stage('test') {

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
