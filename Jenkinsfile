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
        stage('error') {
          steps {
            sh 'echo "prueba 2"'
            retry(count: 5) {
              echo 'vamos a por los 5'
            }

          }
        }
      }
    }
  }
}