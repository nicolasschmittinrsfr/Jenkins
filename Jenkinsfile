pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo 'Building..'
				bat 'cd C:\Users\orsys\Desktop\info-nicolas\jour2-MAVEN\demo\monappli & mvn install'
			}
		}
		stage('Test') {
			steps {
				echo 'Testing..'
			}
		}
		stage('Deploy') {
			steps {
				echo 'Deploying....'
			}
		}
	}
}
