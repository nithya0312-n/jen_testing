pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'git@github.com:nithya0312-n/test_jenkins.git'
            }
        }

        stage('Run Python') {
            steps {
                sh 'python3 factorial.py'
            }
        }
    }
}
