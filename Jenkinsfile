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
            echo "Test Done"
            }
        }
    }
}
