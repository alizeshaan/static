pipeline {
	agent any
	stages {
		stage('Upload to AWS') {
			steps {
			withAWS(credentials='aws-static') {
				def identity = awsIdentity()
				s3Upload(file:'index.html', bucket:'zjenkinsudacitybucket', path:'static/file.txt')
				}	
			}
		}
	}
}
