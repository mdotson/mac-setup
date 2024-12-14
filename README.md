# Prerequisites
```
sudo softwareupdate --install-rosetta
download homebrew
brew install java
brew install ansible
ansible-galaxy collection install geerlingguy.mac
```

# Run:
ansible-playbook -v site.yml --ask-become-pass --extra-vars "user=$USER"

