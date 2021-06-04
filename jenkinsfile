pipeline  {
  agent any 
    stages { 
      stage("Build") {
        steps { 
           echo "building the application"
        }  
       }
      stage("Test"){
       step { 
         echo 'testing the application'
       }
       }
       stage("Deploy"){
       step { 
         echo 'deploying the application'
       }
       }
     }
   }
