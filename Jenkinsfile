pipeline {
	agent {
		label {
			label "built-in"
			customWorkspace "/mnt/data"
		}
	}
	stages {
		stage ("copy-index") {
			steps {
				sh "docker cp /mnt/data/index.html q1:/usr/local/apache2/htdocs/"
			}
		}
	}
}
