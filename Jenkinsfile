node{
	stage('scm'){
		git 'https://github.com/dkc1019/openmrs-core.git'	
	}
	stage('creating artifacts'){
		sh 'mvn package'
	}
}
