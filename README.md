# Prerequisites
```
download homebrew
brew install java
download pip
sudo pip3 install ansible
sudo ansible-galaxy install geerlingguy.homebrew
```

# Run:
ansible-playbook -v site.yml --ask-become-pass --extra-vars "user=$USER"

