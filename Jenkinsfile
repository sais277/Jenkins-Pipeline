pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build Stage"
                cd folder
                python first.py
            }
        }
        stage('Test') {
          steps {
            echo "Test Done"
            }
        }
    }
}
