pipeline {
	agent any
	environment {
		some_string = 123
		some_string = "marek"
	}
	stages{
		stage("Build"){
			steps {
				sh "ls -la"
			}
		}
	}
}
