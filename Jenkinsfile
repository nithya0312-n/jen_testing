pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/nithya0312-n/jen_testing.git',
                    credentialsId: 'admin-neww'
            }
        }

        stage('Run Python Script') {
            steps {
                sh 'python3 factorial.py'
            }
        }
    }
}
