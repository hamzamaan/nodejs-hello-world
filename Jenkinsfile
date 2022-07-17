pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Building the application'
                sh 'npm install'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying the application'
                sh 'npm run start'
            }
        }
    }
}
