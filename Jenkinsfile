pipeline {
	agent any
	stages {
		stage('Upload to AWS') {
			
			steps {
				sh 'echo "testing pipeline"'
				sh 'ls'
				sh 'withAWS(region:"us-east-1",credentials:"aws-static") {s3Upload(file:"index.html", bucket:"zjenkinsudacitybucket")}'
			}
			
		}
	}
}