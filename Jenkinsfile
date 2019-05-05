pipeline{
	agent any 
		stages {
			stage('fetch from git') {
				steps{
					echo 'helo world'
					git credentialsId: '7289cf14-a9a4-4554-9fb0-f467c169bbe4', url: 'https://github.com/GauravGitAccount/first-git.git'
					echo 'bye world'
				}
			}
			stage('maven build'){
				steps{
					echo 'in 2nd step'
				}
			}
			
		}
	
}
