pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Run') {
            steps {
                // Run the hello.py script using Python 3
                sh 'python3 hello.py'
            }
        }
    }
}
