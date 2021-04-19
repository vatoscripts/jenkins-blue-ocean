pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building'
          }
        }

        stage('ParallelBuilding') {
          steps {
            echo 'Parallel Building...'
          }
        }

      }
    }

    stage('Testing') {
      steps {
        echo 'Testing stage...'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying ...'
      }
    }

  }
}