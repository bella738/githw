pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                script {
                git 'https://github.com/bella738/githw.git'
            }
        }
        stage('run python') {
            steps {
                script {
                        sh 'wellcome.py'
                        sh 'click.py'
                    }
                }
            }
        }
    }
}
