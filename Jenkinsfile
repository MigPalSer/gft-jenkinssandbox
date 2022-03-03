
pipeline {
  agent any

  stages {

	stage('test') {

      steps {
        sh echo "ola ke ase jenkins"
      }
      post {
        success {
          sh echo "weeee"
        }
        failure {
          sh echo "buuuuh"
        }
      }
    } //stage    
  } //stages
} //pipeline
