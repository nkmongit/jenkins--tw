pipeline {
  agent any
  stages {
    stage('Checking In') {
      steps {
        sh 'echo "Checking In"'
      }
    }

    stage('Install Node') {
      steps {
        sh '''sudo apt-get install node

cat node --version'''
      }
    }

  }
}