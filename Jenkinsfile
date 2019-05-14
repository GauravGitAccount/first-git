properties([parameters([choice(choices: ['master', 'feature'], description: 'Please select the branch', name: 'Branch')])])
pipeline{
	agent any 
	tools{
		maven 'maven_3.6.1'
		
	}
		stages {
			stage('maven build'){
				steps{
					
					echo "${params.Branch}"
					echo 'start'
					echo "M2_HOME = ${M2_HOME}"
					echo "PATH = ${PATH}"
					bat 'mvn compile'
					echo 'stop'
					
				}
			}
			
		}
	
}
