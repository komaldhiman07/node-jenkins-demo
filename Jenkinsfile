pipeline {
  agent any
    
  tools {NodeJS "node"}
    
  stages {
        
    stage('Deploy') {
      steps {
        sh 'npm install'
         sh 'npm start'
      }
    }  
  }
}