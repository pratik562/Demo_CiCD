pipeline {
    agent {
            node {
                label "main"  //change this as per your agent label
            }
        }
     environment {
            CI = 'true'
        }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}