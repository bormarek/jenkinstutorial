pipeline {
	agent any
	environment {
		some_number = 123
		some_string = "marek"
	}
	stages{
		stage("Build"){
			steps {
				sh "ls -la"
			}
		}
		stage("Test"){
			steps {
				sh "mvn -version"
			}
		}
	}
}
