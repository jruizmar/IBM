pipeline {
  agent any
  stages {
    stage('Inicio') {
      steps {
        echo 'Hola desde stage Inicio'
      }
    }
    stage('Test2') {
      agent any
      steps {
        echo 'Hola desde Test2'
      }
    }
  }
}