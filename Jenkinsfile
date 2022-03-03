
pipeline {
  agent any

  stages {

	stage('test') {

      steps {
        script{
          sh echo "ola ke ase jenkins"}
      }
      post {
        success {
          script{
          sh echo "weeee"}
        }
        failure {
          script{
          sh echo "buuuuh" }
        }
      }
    } //stage    
  } //stages
} //pipeline
