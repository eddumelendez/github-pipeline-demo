pipeline {
    agent label: ''

    stages {
        stage('Build') {
            when {
                env.BRANCH_NAME == 'develop'
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
