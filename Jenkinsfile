pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Etapa de construccion'
      }
    }

    stage('test') {
      steps {
        echo 'Esta es la etapa de Pruebas'
        sh './ejemplo_while.sh'
      }
    }

    stage('staging') {
      steps {
        echo 'Etapa de consolidacion'
      }
    }

    stage('deploy') {
      steps {
        echo 'Etapa de entrega'
      }
    }

  }
}