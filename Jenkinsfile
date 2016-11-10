node () {
	checkout scm
    if (env.JOB_NAME =~ 'myjob1') {
        load 'Smoke.Jenkinsfile.groovy'
	}
	else {
		load 'Regression.Jenkinsfile.groovy'
	}
}