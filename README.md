# Prerequisites
```
download homebrew
brew install java
brew install python
pip3 install ansible
ansible-galaxy collection install geerlingguy.mac
```

# Run:
ansible-playbook -v site.yml --ask-become-pass --extra-vars "user=$USER"

