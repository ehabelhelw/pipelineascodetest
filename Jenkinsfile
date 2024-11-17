pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build complete '
        timeout(time: 5, unit: 'SECONDS') {
         sh 'sleep 2'
        }
      }
    }

 stage('Test') {
      steps {
        echo 'testing completed '
      }
    }

    stage('deploy') {
      steps {
        echo 'deploying completed '
      }
    }

  }
}