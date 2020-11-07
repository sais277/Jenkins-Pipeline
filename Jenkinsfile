pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "$(python hello.txt)"
            }
        }
        stage('Test') {
          steps {
            cd folder
            python first.py
            }
        }
    }
}
