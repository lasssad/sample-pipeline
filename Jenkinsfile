node {
   
   	stage 'Stage 1'
   		echo 'Hello there, shell scripts'
   		
   	stage 'Checkout'
   		git url: 'https://github.com/lasssad/sample-pipeline.git'
   	stage 'Build'
   			sh './myBuild.sh'
   		echo 'Hello there, shell Build'
   	stage 'Deploy'
   		echo 'Hello there, shell Deploy'
  
}