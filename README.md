sudo easy\_install pip
pip install ansible
pip install setuptools  

ansible-galaxy install geerlingguy.homebrew --roles-path .

If that last command fails, we need xcode:
xcode-select --install

Run:
ansible-playbook -v site.yml --ask-sudo-pass
