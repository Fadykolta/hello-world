
pipeline {
  
    agent any
  
    stages {
  
        stages("build") {
    
               steps {
                   echo 'building the application...'
      
              }
        }
        stages("test") {
    
             steps {
                 echo 'testing the application...'
  
            }
       }
       stage("deploy") {
    
           steps {
               echo 'deploying the application...'
     
          }
      }
   }
}
