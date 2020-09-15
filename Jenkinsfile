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
                        sh 'wellcome.py'
                        sh 'Click.py'
                    }
                }
            }
        }
    }
}
