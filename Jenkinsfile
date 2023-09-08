pipeline {
	agent {
		label {
			label "built-in"
			
		}
	}
	stages {
		stage ("playbook-run") {
			steps {
				sh "rm -rf /var/www/html/*"
				sh "chmod 777 /var/www/html"
				sh "cp /var/lib/jenkins/workspace/test_23Q1/index.html /var/www/html/"
				
			}
		}
	}
}
