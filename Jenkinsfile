pipeline {
    agent any // This specifies that the pipeline can run on any available agent
    stages {
        stage('build') {
            steps {
                // Directly run commands on the Jenkins agent
                sh 'python --version'
                // Additional steps can be added here as needed
            }
        }
        // You can add more stages for testing, deploying, etc.
    }
}
