pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo 'Building..'
				clean package
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
