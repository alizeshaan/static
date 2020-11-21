pipeline {
	agent any
	stages {
		stage('Upload to AWS') {
			
			steps {
				sh 'echo "testing pipeline"'
				sh '''
					withAWS(region:'us-east-1',credentials='aws-static'){
						Upload(file:'index.html', bucket:'zjenkinsudacitybucket', path:'**/*')
						}
				   '''
			}
			
		}
	}
}
