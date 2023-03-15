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
				sh "docker exec -it q2 bash"
				sh "chmod 777 /usr/local/apache2/htdocs/index.html
			}
		}
	}
}
