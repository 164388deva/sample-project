pipeline {
	agent any
	
	stages {
		stage("Build Stage"){
			steps {
				echo 'Building Project'
				sh 'mvnw clean package'
			}
		}
	}
}
