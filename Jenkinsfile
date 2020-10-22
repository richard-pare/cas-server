pipeline {
  agent any
  stages {
    stage('bonjour') {
      parallel {
        stage('bonjour') {
          steps {
            echo 'Étape 1'
          }
        }

        stage('salut') {
          steps {
            echo 'salut'
          }
        }

        stage('aureveroir') {
          steps {
            sleep 1
          }
        }

      }
    }

  }
}