pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/rohithvelakatoori/jenkins.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building project..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying project..."'
            }
        }
    }
}
