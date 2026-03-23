pipeline {
    agent any

    tools {
        // Make sure Python is installed and configured in Jenkins
        python 'Python_3'
    }

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/nithya0312-n/jen_testing.git'
            }
        }

        stage('Run Script') {
            steps {
                // Run the Python script directly
                sh 'file1.py'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished!'
        }
    }
}

