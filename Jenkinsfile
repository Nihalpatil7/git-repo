pipeline {
	agent {
		label {
			label "built-in"
			
		}
	}
	stages {
		stage ("copy-index") {
			steps {

				sh "cp /var/lib/jenkins/workspace/test_23Q3/index.html /var/www/html/"
			}
		}
	}
}
