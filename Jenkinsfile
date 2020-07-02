pipeline {
  agent any
  stages {
    stage('dependencies') {
      steps {
        '\'npm i\''
      }
    }

    stage('build') {
      steps {
        'echo \'build process\''
      }
    }

    stage('e2e tests') {
      steps {
        '\'npm run test\''
      }
    }

  }
}
