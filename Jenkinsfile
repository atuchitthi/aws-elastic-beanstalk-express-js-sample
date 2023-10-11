pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
   stage('Build') {
      steps {
        sh 'npm install --save'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing the application'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying the application'
      }
    }
  }
}
