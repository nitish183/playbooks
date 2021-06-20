pipeline{
	agent any 
	stages{
		stage("Execute playbook"){
			steps{
			ansiblePlaybook credentialsId: 'ssh_key', installation: 'ansible', inventory: './inventory.ini', playbook: './playbook.yml'
			}
		}
	}
}