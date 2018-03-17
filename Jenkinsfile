pipeline {
  agent any
  stages {
    stage('Initialize') {
      parallel {
        stage('Initialize') {
          steps {
            echo 'Welcome to my pipeline'
            sh 'whoami'
            sh 'pwd'
            sh 'df -h'
          }
        }
        stage('Initialize Step 10') {
          steps {
            sh 'vm_stat'
          }
        }
      }
    }
  }
}