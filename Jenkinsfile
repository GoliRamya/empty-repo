pipeline {
  agent any
  stages {
    stage('plan') {
      parallel {
        stage('plan') {
          steps {
            echo 'there is a plan to work on cicd'
          }
        }

        stage('code') {
          steps {
            echo 'code is ready'
          }
        }

      }
    }

  }
}