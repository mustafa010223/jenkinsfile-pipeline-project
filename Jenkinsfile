pipeline {
    agent any
    stages {
        stage('Build Java Code') {
            steps {
                echo 'Compiling the Java source code'
                sh 'javac Hello.java'
            }
        }
        stage('Run Java Code') {
            steps {
                echo 'Running the compiled Java code'
                sh 'java Hello'
            }
        }
    }
}

