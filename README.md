# Prerequisites
```
sudo easy\_install pip
pip install ansible
pip install setuptools
ansible-galaxy install geerlingguy.homebrew --roles-path .
```

# Run:
ansible-playbook -v site.yml --ask-sudo-pass

