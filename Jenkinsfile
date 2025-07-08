pipeline{
  	agent any
	tools {
		nodeJS 'nodejs-24-3-0'
	}
	stages {
		stage("Installing deps"){
			steps{
				sh '''
					node -v
					npm -v
				'''
			}
		}
	}

}
