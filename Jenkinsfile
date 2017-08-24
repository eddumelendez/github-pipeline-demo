pipeline {
    agent any

    stages {
        stage('Build') {
            when {
                branch 'develop'
            }
            steps {
                echo "Building..."
            }
        }
        stage('Test') {
            steps {
                echo "Testing..."
            }
        }
    }

}
