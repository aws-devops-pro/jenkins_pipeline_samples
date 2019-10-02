node {
//echo 'Pulling...' + env.BRANCH_NAME
//echo 'Pulling... ' + env.GIT_BRANCH
if (env.BRANCH_NAME == "develop") {
	stage ('Build The Env') {
	echo " Building the Dev env"
	}
   stage ('Deploy into Dev env') {
	echo " Deploy into Dev Env"
}
	stage ('Test in Dev env') {
		echo " Testing the Dev env "
	}
  	

}

if (env.BRANCH_NAME == "master") {
   stage ('Deploy into Master env') {
        echo " Deploy into Master Env"
}

} 
	if (env.BRANCH_NAME == "release") {
   stage ('Deploy into INT env') {
        echo " Deploy into INT Env"
}
		stage ('test in INT Encv') {
			echo "Test in iNT Env"
		}

} 

}
