pipeline {
    agent { docker { image 'python:alpine' } }
    stages {
        stage('run') {
            steps {
                echo 'Hey Jason Time to Reinvent Yourself'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}

