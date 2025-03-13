pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code...'
                git 'https://github.com/Badamaranahalli123/PES1UG22AM081_jekins.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'echo "Build successful!"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Tests passed!"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo "Deployment successful!"'
            }
        }
    }

    post {
        always {
            echo 'Pipeline execution completed by Karthik BK.'
        }
    }
}
