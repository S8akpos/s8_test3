pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                // Your build steps are here
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                // Your test steps are here
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                // Your deployment steps are here
                echo 'Deploying...'
            }
        }
        stage (listing) {
            steps {
                script {
                    sh """
                    ls -l
                    """
                }
            }
        }
    }
}
