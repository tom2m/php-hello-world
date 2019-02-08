node {
	stage('buildImage'){
		openshiftBuild(buildConfig: 'php-sample-app', showBuildLogs: 'true')
	}
	
	stage('deployApplication'){
		openshiftDeploy(deploymentConfig: 'php-sample-app')
	}
}