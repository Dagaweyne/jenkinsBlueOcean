pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building...'
          }
        }

        stage('ParallelBuild') {
          steps {
            echo 'Building in paralell...'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'testing...'
      }
    }

    stage('Publish') {
      steps {
        echo 'publish...'
      }
    }

  }
}