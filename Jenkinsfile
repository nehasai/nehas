node {
	stage('build') {
		configFileProvider([configFile(fileId: 'config', variable: 'MAVEN_SETTINGS_XML')]) {
			def mvnHome = tool name: 'maven3', type: 'maven'
			def mvnCMD = "${mvnHome}/bin/mvn"
			sh "${mvnCMD} -s $MAVEN_SETTINGS_XML clean package"
            }
	}
        
}
    
 

