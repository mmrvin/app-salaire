node{
 stage('Clone') {
 git 'https://github.com/mmrvin/app-salaire/tree/master/roles.git'
 }
 stage('Ansible') {
 ansiblePlaybook (
 colorized: true, 
 become: true, 
 playbook: 'launcher.yml',
 inventory: 'hosts.yml'
 )
 }
}
