pipeline {
	agent any
	
	stages {
		stage("Build Stage"){
			echo 'Building Springboot maven project'
			sh 'mvn clean package'
		}
	}
}
