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
				sh "docker cp /mnt/data/index.html 23Q1:/usr/local/apache2/htdocs/"
			}
		}
	}
}
