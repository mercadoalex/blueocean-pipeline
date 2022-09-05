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
        sh "chmod +x -R ${env.WORKSPACE}"
        sh './ejemplo_while.sh'
        echo 'Esta es la etapa de Pruebas'
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