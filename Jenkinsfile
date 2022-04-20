pipeline {
	agent { docker { image 'maven:3.6.3'} }
	stage('Build') {
		steps {
			echo "mvn --version"
			echo "Build"
		}
	}
	stage('Test') {
		echo "Test"
	}
	stage('Integration Test') {
		echo "Test"
	}
}
