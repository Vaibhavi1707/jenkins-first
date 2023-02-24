pipeline {
  agent any
  stages {
    stage('Checkout code') {
      steps {
        git(url: 'https://github.com/Vaibhavi1707/jenkins-first', branch: 'main')
      }
    }

    stage('Log') {
      steps {
        sh 'python3 hello.py'
      }
    }

    stage('Build') {
      steps {
        sh 'echo "Build"'
      }
    }

  }
}