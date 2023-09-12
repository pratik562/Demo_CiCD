pipeline {
  agent any
  tools {
      nodejs "node"
      
  }
  stages {
    stage('Build') {
      steps {
        git branch: 'main', url: 'https://github.com/pratik562/Demo_CiCD.git'
        sh 'npm install'
        sh 'npm test'
        sh 'npm android:build:debug'
      }
        
    }
      
  }
    
}