pipeline {
    agent any 
    stages {
        stage('Build'){
            steps{
                bat 'npm install'

            }
        }
        stage('Run Powershell Command'){
			steps{
				echo 'Start Executing'
				script{
					powershell '''
				c:\\test-script\\myscript.ps1
					'''
				}
			}
		}
    }
}