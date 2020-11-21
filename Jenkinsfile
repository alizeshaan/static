pipeline {
	agent any
	stages {
		stage('Upload to AWS') {
			
			steps {
				sh 'echo "testing pipeline"'
				sh 'ls'
				withAWS(region:"us-east-1",credentials="aws-static"){
				sh 'echo "hi there"'
				}
			}
			
		}
	}
}
