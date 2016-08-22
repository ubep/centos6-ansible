
install git and add ssh key to GitHub

    ansible-playbook -i inventory -s -k -u root playbooks/git.yml

install tools

    ansible-playbook -i inventory -s -k -u root playbooks/tools.yml

configure iptables

    ansible-playbook -i inventory -s -k -u root playbooks/iptables.yml

install ruby

    ansible-playbook -i inventory -s -k -u root playbooks/ruby.yml
