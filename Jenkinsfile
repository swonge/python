// Powered by Infostretch 

timestamps {

node () {

	stage ('Build Python - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'github_id', url: 'https://github.com/swonge/python']]]) 
	}
}
}