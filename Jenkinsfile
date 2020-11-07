pipeline {
    agent { label 'master' }
    stages {
        stage('Build') {
            steps {
                echo "Build Stage"
                sh "python hello.py"
            } 
        }
        stage('Test') {
          steps {
            sh 'cd $(pwd)/folder'
            sh 'python $(pwd)/folder/first.py'
            echo "Test Done"
            }
        }
    }
}
