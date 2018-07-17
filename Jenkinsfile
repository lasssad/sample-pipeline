node {
   
   	stage 'Stage 1'
   		echo 'Hello there, shell scripts'
   	
   	stage 'Setting the variables values' 
    
         bash '''#!/bin/bash
                 echo "hello world" 
         '''
    
   	stage 'Checkout'
   		git url: 'https://github.com/lasssad/sample-pipeline.git'
   	stage 'Build'
   			
   		echo 'Hello there, shell Build'
   	stage 'Deploy'
   		echo 'Hello there, shell Deploy'
  
}