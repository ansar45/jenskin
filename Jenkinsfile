<<<<<<< HEAD

de{
=======
node{
>>>>>>> bfcab70e595556cf0b1ab03474e74ae72c84c908
    stage('Clone') {
        checkout scm
    }
    stage('Ansible') {
      ansiblePlaybook (
          colorized: true,          
          playbook: 'playbook.yml',
          inventory: 'hosts.yml'
      )
    }
}
