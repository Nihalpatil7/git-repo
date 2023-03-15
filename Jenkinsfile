pipeline {
	agent {
		label {
			label "built-in"
			customWorkspace "/mnt/project"
		}
	}
	stages {
		stage ("copy-index") {
			steps {
				sh "docker cp /mnt/project/index.html q2:/usr/local/apache2/htdocs/"
				
				sh "chmod 777 q2:/usr/local/apache2/htdocs/index.html"
			}
		}
	}
}
