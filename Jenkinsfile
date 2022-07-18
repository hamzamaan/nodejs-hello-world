pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Building the application'
                sh 'npm version'
            }
        }
//         stage('deploy') {
//             steps {
//                 echo 'deploying the application'
//                 sh 'npm start'
//                 // sh 'nohup npm start&'
           // }
      //  }
    }
}
