pipeline {
    agent any
    stages {
        stage('Run Python Script') {
            steps {
                echo 'Running Python script inside Jenkins Pipeline'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}

