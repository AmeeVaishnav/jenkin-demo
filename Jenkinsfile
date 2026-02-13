pipeline (
  agent any

  stages {
    stage ('Clone'){
      steps{
        echo 'Clone repository..'
      }
    }
    
    stage ('Install'){
      steps{
        sh 'npm install'
      }
    }
    
    stage ('Run'){
      steps{
        sh 'npm start'
      }
    }
  }
)
