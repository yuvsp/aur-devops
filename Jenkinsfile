pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }

    stages {
        stage('Run Python Script') {
            steps {
                sh 'main.py'
            }
        }
    }
}


