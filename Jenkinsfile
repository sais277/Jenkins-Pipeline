pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build Stage"
                sh "python hello.py"
            } 
        }
        stage('Test') {
          steps {
            sh 'cd folder'
            sh 'python first.py'
            echo "Test Done"
            }
        }
    }
}
