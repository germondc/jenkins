pipeline {
	agent {
		dockerfile true
	}
	stages {
		stage('Example') {
			steps {
				echo 'hello'
				sh 'echo var: $test_var'
			}
		}
	}
}
