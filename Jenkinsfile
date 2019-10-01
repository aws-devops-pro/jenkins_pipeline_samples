node {
//echo 'Pulling...' + env.BRANCH_NAME
echo 'Pulling... ' + env.GIT_BRANCH
if (env.BRANCH_NAME == "develop") {
   stage ('Deploy into Dev env') {
	echo " Deploy into Dev Env"
}

}

if (env.BRANCH_NAME == "master") {
   stage ('Deploy into INT env') {
        echo " Deploy into INT Env"
}

} 

}
