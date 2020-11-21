pipeline {
	agent any
	stages {
		stage('Upload to AWS') {
			
			steps {
				sh 'echo "testing pipeline"'
				sh 'ls'
				sh 'withAWS(credentials="aws-static"){def identity = awsIdentity()}'
			}
			
		}
	}
}
