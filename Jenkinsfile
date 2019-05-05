pipeline{
	agent any 
	tools{
		maven 'maven_3.6.1'
		
	}
		stages {
			stage('maven build'){
				steps{
					echo 'start'
					tool name: 'maven_3.6.1', type: 'maven'
					
					echo 'stop'
					
				}
			}
			
		}
	
}
