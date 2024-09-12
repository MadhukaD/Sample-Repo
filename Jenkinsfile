pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/MadhukaD/Sample-Repo', branch: 'main')
      }
    }

    stage('Listing Out files') {
      steps {
        sh 'ls -la'
      }
    }

  }
}