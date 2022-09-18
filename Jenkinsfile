pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/vesteves33/kube-news', branch: 'main')
      }
    }

    stage('Log') {
      steps {
        sh 'ls = la'
      }
    }

  }
}