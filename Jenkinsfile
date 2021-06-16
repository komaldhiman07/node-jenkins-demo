pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
        
    stage('Deploy') {
      steps {
        sh 'npm install'
         sh 'npm start'
      }
    }  
  }
}