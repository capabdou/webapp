ansible-playbook -i hosts.yml --ask-vault-pass deploy.yml
ansible-vault encrypt credentials.yml


pour envoyer à git
git init
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/capabdou/webapp.git
ssh-keygen -t rsa et mettre le pub dans github
git remote set-url origin git@github.com:capabdou/webapp.git
git branch -M main
git push -u origin main
