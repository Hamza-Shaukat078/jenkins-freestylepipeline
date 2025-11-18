pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Building the project..."
                sh 'echo Build Step Running'
                // Example for Node projects:
                // sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo Test Step Running'
                // Example:
                // sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the project..."
                sh 'echo Deploy Step Running'
                // Example:
                // sh './deploy.sh'
            }
        }
    }
}
