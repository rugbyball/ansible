ref: http://docs.ansible.com/ansible/playbooks_vault.html  

ansible-vault edit *.yml --vault-password-file=keyfile  
ansible-vault encrypt *.yml --vault-password-file=keyfile   
ansible-vault decrypt *.yml --vault-password-file=keyfile   
