pipeline{
  	agent any
	tools {
		nodejs 'nodejs-24-3-0'
	}
	stages {
		stage("Installing deps"){
			steps{
				bat '''
					node -v
					npm -v
					echo "hehe bitch"
				'''
			}
		}
	}

}
