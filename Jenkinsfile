node{
	stage('scm'){
	git 'https://github.com/devopstraining4/baby1'
	}
	stage {'Compilation'){
		def mvnHome = tool name: 'maven2', type: 'maven') 
	        sh 'mvn package'
	}
