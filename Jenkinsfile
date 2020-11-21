pipeline {
<<<<<<< HEAD
	agent any
	stages {
		stage('Upload to AWS') {
			steps {
			withAWS(region:'us-east-1', credentials='aws-static') {
				s3Upload(file:'index.html', bucket:'zjenkinsudacitybucket', path:'file.txt')
				}
				
			}
		}
	}
=======
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello World"'
        sh '''
					echo "Multiline shell steps work too"
					ls -lah
				'''
      }
    }

  }
>>>>>>> c26bba8ec0764c5c4d1f6f141db2e79e220f3965
}