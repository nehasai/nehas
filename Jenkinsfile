node {
	stage('build') {
			git branch: 'develop', url: 'https://github.com/nehasai/nehas.git'
			def mvnHome = tool name: 'maven3', type: 'maven'
			def mvnCMD = "${mvnHome}/bin/mvn"
			sh "${mvnCMD} clean package"
            }
	}
        

    
 

