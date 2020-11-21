pipeline {
	agent any
	options{
		withAWS(region:'us-east-1',credentials='aws-static')
		}
	stages {
		stage('Upload to AWS') {
			steps {
				s3Upload(file:'index.html', bucket:'zjenkinsudacitybucket', path:'**/*')
			}
		}
	}
}
