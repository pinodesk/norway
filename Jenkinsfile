pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Building...'
        sh './mvnw test-compile'
      }
    }

  }
}