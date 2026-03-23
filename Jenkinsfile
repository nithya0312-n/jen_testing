pipeline {
    agent any

    tools {
        jdk 'Java_17'
    }

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/nithya0312-n/jen_testing.git'
            }
pipeline {
    agent any

    tools {
        jdk 'Java_17'
    }

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/nithya0312-n/jen_testing.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'file1.java'
            }
        }

        stage('Run') {
            steps {
                // Pass a name as input via environment variable
                sh 'echo "Nithya" | java Greeting'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished!'
        }
    }
}
        }

        stage('Compile') {
            steps {
                sh 'javac Greeting.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Greeting'
            }
        }
    }
}

