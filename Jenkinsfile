pipeline{
	agent any 
	stages{
		stage("Execute playbook"){
			steps{
			ansiblePlaybook credentialsId: 'osboxes', installation: 'ansible', inventory: './inventory.ini', playbook: './playbook.yml'
			}
		}
	}
}