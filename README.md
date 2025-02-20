ansible-playbook -i hosts.yml --ask-vault-pass deploy.yml
ansible-vault encrypt credentials.yml
