pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', credentialsId: 'GitHub_Credentials', url: 'https://github.com/ranjanisengottaian/assignment_84/'  }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}