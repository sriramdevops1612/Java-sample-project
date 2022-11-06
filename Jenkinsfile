pipeline {
    agent any
    stages {
	    stage ('Build') {
          steps{
              
              sh "sleep 5"
              
          } 
        }
        stage ('Run Tests') {
            parallel {
                stage ('Test On Windows') {
                   steps{
              
                          sh "sleep 5"
                          
                    } 
                }
                stage ('Test On Linux') {
                     steps{
              
                          sh "sleep 5"
                          
                      } 
                }
            }
        }
    }
}
