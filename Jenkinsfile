pipeline {
	agent {
		label {
			label "built-in"
			customWorkspace "/mnt/project"
		}
	}
	stages {
		stage ("playbook-run") {
			steps {
				sh "ansible-playbook test.yaml"
			}
		}
	}
}
