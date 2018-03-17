pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Welcome to my pipeline'
        sh '''whoami 

&& pwd && df -h
'''
      }
    }
  }
}