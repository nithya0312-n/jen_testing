pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull code from your GitHub repo
                git branch: 'main', url: 'https://github.com/nithya0312-n/jen_testing.git'
            }
        }

        stage('Run Python Script') {
            steps {
                // Run using system-installed Python 3.10.12
                sh 'factorial.py'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished!'
        }
    }
}

