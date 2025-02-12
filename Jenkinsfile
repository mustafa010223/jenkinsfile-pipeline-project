pipeline {
    agent any
    stages {
        stage('Polling SCM') {
            steps {
                echo 'Checking for changes in GitHub repo...'
                sh 'echo SCM polling triggered this build'
            }
        }
    }
}

