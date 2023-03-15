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
				sh "docker cp /mnt/project/index.html 23Q1:/usr/local/apache2/htdocs/"
			}
		}
	}
}
