node{
	stage('scm'){
		git branch: 'feature1', url: 'https://github.com/dkc1019/openmrs-core.git'
	}
	
	Stage(‘junit test result’){         
	junit '/surefire-target/*.xml'
	}
}