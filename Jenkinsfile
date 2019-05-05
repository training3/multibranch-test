pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
            }
        }
	stage('only if test1'){
		when {
 		  branch 'test1'
			}
		steps {
		sh 'echo "running from test1 branch"'
    }
}}}
