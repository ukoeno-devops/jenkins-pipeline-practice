pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/ukoeno-devops/jenkins-pipeline-practice.git',
                    credentialsId: 'github-token'
            }
        }
        stage('Test Connection') {
            steps {
                echo "✅ Jenkins successfully connected to GitHub and cloned the repository."
            }
        }
    }
}

