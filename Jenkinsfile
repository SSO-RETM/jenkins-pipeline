pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        sleep 20
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('continue to deploy') {
      steps {
        input(message: 'continue', ok: 'Yes')
      }
    }
  }
}