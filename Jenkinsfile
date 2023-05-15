pipeline {
    agent any
    stages {
        stage('Push Ansible configuration to install docker') {
			steps {
                sh 'ansible-playbook playbook.yml'
            }
        }
}
}
