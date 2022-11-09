pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo 'Building..'
				bat 'cd monappli & mvn install'
			}
		}
		stage('Test') {
			steps {
				echo 'Testing..'
				junit '**/target/**/*.xml'
			}
		}
		stage('Deploy') {
			steps {
				echo 'Deploying....'
				bat 'copy "C:\\Users\\orsys\\.jenkins\\workspace\\Mon job free-style Git-Junit\\monappli-web\\target\\monappli-web.war" "C:\\Program Files\\Apache Software Foundation\\Tomcat 9.0\\webapps\\monappli-web.war" /Y'
			}
		}
	}
}
