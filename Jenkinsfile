pipeline{
	agent any 
		stages {
			stage('fetch from git') {
				steps{
					checkout changelog: false, poll: false, scm: [$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'b2fe809e-e89b-4136-a4bd-fe6badf359d4', url: 'git@github.com:GauravGitAccount/first-git.git']]]
				}
			}
		}
	
}
