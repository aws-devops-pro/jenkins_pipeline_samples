node {
	
if (env.BRANCH_NAME == "develop") {
	stage ('Build The Env') {
	echo " Building the Dev env
	}
   stage ('Deploy into Dev env') {
	echo " Deploy into Dev Env"
}
	stage ('Test in Dev env') {
		echo " Testing the Dev env "
	}
	slackSend channel: '#july-devops', color: 'bad', message: "Success --> ${env.JOB_NAME} ${env.BUILD_NUMBER} (<${env.BUILD_URL}|Open>)", teamDomain: 'sspcloudpro', tokenCredentialId: 'tokensspslack', username: 'sspcloudpro'
  	

}

if (env.BRANCH_NAME == "master") {
   stage ('Deploy into Master env') {
        echo " Deploy into Master Env"
}
	slackSend channel: '#july-devops', color: 'bad', message: "Success --> ${env.JOB_NAME} ${env.BUILD_NUMBER} (<${env.BUILD_URL}|Open>)", teamDomain: 'sspcloudpro', tokenCredentialId: 'tokensspslack', username: 'sspcloudpro'

} 

}
