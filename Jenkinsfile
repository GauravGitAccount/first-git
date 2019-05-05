pipeline{
	agent any 
	tools{
		maven 'maven_3.6.1'
		
	}
		stages {
			stage('maven build'){
				steps{
					echo 'start'
					echo "M2_HOME = ${M2_HOME}"
					batch 'mvn compile'
					echo 'stop'
					
				}
			}
			
		}
	
}
