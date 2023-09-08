pipeline {
	agent {
		label {
			label "built-in"
			
		}
	}
	stages {
		stage ("copy-index") {
			steps {
				sh "cp /var/lib/jenkins/workspace/master/index.html /var/www/html/"
			}
		}
	}
}
