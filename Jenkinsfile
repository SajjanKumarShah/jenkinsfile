pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "sajjan here to save world"
pwd'''
        echo 'Test completed'
        echo 'tested'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'testing done'
          }
        }

        stage('test2') {
          steps {
            sh 'echo "sajjan"'
          }
        }

      }
    }

    stage('build completed') {
      steps {
        sleep 3
      }
    }

  }
}