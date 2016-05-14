sudo easy\_install pip  
sudo easy\_install ansible  
sudo easy\_install -U setuptools  

sudo ansible-galaxy install geerlingguy.homebrew
ansible-playbook -v site.yml --ask-sudo-pass
