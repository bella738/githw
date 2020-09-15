pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/bella738/githw.git'
            }
        }
        stage('run python') {
            steps {
                sh 'python wellcome.py'
                sh 'python click.py'
            }
        }
    }
}
