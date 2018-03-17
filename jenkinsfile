// my test jenkinsFile

pipeline {
    agent any
    stages {
        stage('welcome') {
            steps {
                echo "Hello welcome to this test"
                sh "whoami && pwd && df -h"
            }
        }
        stage('end') {
            steps {
                echo "That's all there is."
                echo "Goodbye."
            }
        }
        
    }
}
