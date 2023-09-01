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
				sh "cp index.html /var/www/html/"
				sh "chmod 777 /var/www/html/index.html"
			}
		}
	}
}
