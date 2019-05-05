pipeline{
	agent any 
	tools{
		maven 'maven_3.6.1'
		jdk 'jdk_9.0.4'
	}
		stages {
			stage('maven build'){
				steps{
					echo 'start'
					echo "M2_HOME = ${M2_HOME}"
					echo "PATH = ${PATH}"
					bat 'mvn compile'
					echo 'stop'
					
				}
			}
			
		}
	
}
