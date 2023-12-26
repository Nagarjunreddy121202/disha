@Library ('My-Jenkins-sharedLibrary')_
pipeline {
agent any  

  stages{
    stage ('Build'){
      steps{
        script{
          build()
          
        }
      }
    }
    Stage ('Deploy'){
      steps{
        script{
          deplodemo()
          
        }
      }
      
    }
  }
    
}
