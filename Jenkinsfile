pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/nunidoron/lesson7-targil.git'
                sh 'python main.py'
            }
        }
    }
}
