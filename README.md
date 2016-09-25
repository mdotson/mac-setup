python get-pip.py
pip install ansible
sudo easy\_install -U setuptools  

ansible-galaxy install geerlingguy.homebrew

If that last command fails, we need xcode:
xcode-select --install

Run:
ansible-playbook -v site.yml --ask-sudo-pass
