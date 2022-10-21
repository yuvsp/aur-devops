pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }

    stages {
        stage('Run Python Script') {
            steps {
                echo 'Running..'
                sh 'main.py'
            }
        }
    }
}
