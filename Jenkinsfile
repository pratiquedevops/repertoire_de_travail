node{

   stage('Clone')  {
        git 'https://github.com/pratiquedevops/repertoire_de_travail.git'
  }
   stage('Ansible')  {

   sh 'ansible-playbook -i hosts.yml  playbook.yml'

    }
  }
