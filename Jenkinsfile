pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'python main.py'
            }
        }
        stage('Hi from new stage') {
            steps {
                sh 'python main.py'
            }
        }
    }
}
