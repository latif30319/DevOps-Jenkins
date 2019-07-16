// Declarative //
pipeline {

	agent any
	
	stages {
		stage('Build') {
			steps {
				echo 'Building..XXXXXXXXXXXXXX'
			}
		}
		stage('Test') {
			steps {
				echo 'Testing..'
			}
		}
		stage('Deploy') {
			steps {
				echo 'Deploying....YYYYYYYYYYYYYY'
				}
			}
		}
	}
// Script //
node {
	stage('Build') {
		echo 'Building....'
	}
	stage('Test') {
		echo 'Building....'
	}
	stage('Deploy') {
		echo 'Deploying....'
	}
}
