pipeline {
  agent any
  stages {
    stage('Initialize') {
      parallel {
        stage('Initialize') {
          steps {
            echo 'Welcome to my pipeline'
            sh 'whoami && pwd && df -h'
          }
        }
        stage('Initialize Step 10') {
          steps {
            sh 'vm_stat'
          }
        }
        stage('Initialize Step 20') {
          environment {
            myJobName = 'helloWorld3'
          }
          steps {
            echo '$myJobName'
          }
        }
      }
    }
  }
  environment {
    myJobName = 'helloWorld3-Job'
  }
}