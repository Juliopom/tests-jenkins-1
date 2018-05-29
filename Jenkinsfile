pipeline {
  agent any
  stages {
    stage('Buid') {
      parallel {
        stage('Buid') {
          steps {
            echo 'Esto es un mensaje de prueba'
          }
        }
        stage('') {
          steps {
            sh 'echo "prueba 2"'
          }
        }
      }
    }
  }
}