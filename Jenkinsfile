pipeline {
  agent any
  stages {
    stage('Build Step 1') {
      parallel {
        stage('Build Step 1') {
          steps {
            sh 'echo "Step 1"'
          }
        }
        stage('Build Step 2 ') {
          steps {
            sh 'echo "step 2"'
          }
        }
      }
    }
    stage('Deploy to Dev') {
      steps {
        sh 'echo "Deploying to Dev"'
      }
    }
  }
}