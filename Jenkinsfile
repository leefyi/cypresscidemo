pipeline {
  agent any
  stages {
    stage('dependencies') {
      steps {
        sh '\'npm i\''
      }
    }

    stage('build') {
      steps {
        sh 'echo \'build process\''
      }
    }

    stage('e2e tests') {
      steps {
        sh '\'npm run test\''
      }
    }

  }
}