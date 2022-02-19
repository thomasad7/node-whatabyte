pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        bat '%NODE_HOME%/npm install'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
