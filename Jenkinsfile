pipeline {
  agent any
  stages {
    stage('Buid') {
      steps {
        echo 'Esto es un mensaje de prueba'
      }
    }
    stage('Delete') {
      steps {
        cleanWs(cleanWhenSuccess: true, skipWhenFailed: true)
      }
    }
  }
}