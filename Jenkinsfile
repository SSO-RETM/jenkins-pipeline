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
        input(message: 'continue', ok: 'Yes', parameters: [booleanParam(defaultValue: true, 
                        description: 'If you like to deploy, just push the button',name: 'Yes?'))
      }
    }
  }
}
