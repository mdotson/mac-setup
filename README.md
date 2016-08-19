sudo easy\_install pip  
sudo easy\_install ansible  
sudo easy\_install -U setuptools  

sudo ansible-galaxy install geerlingguy.homebrew

If that last command fails, we need xcode:
xcode-select --install

Run:
ansible-playbook -v site.yml --ask-sudo-pass
