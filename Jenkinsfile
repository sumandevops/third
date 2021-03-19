pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'building the code'
          }
        }

        stage('Test') {
          steps {
            echo 'this is test stage'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy the code'
      }
    }

  }
}