pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
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
     stage('Deploy') {
      steps {
        echo 'Success you have deployed!'
      }
    }
  }
}
