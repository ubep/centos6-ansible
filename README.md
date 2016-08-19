
install git

    ansible-playbook -i inventory -s -k -u root playbooks/git.yml

install tools

    ansible-playbook -i inventory -s -k -u root playbooks/tools.yml


