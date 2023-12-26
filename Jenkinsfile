pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the PHP project...'
                // Add your build commands here if needed
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the PHP project...'
                // Add your deployment commands here if needed
            }
        }
    }
    post {
        success {
            echo 'The CI/CD pipeline ran successfully!'
        }
    }
}
