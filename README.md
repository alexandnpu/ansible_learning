# how to run

ansible app_servers --extra-vars "ansible_ssh_pass=your_ssh_password" -m command -a putime
ansible-playbook hg.yml -e "ansible_ssh_pass=your_ssh_password”


