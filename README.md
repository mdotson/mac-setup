# Prerequisites
```
java -version
sudo easy_install pip
sudo pip install ansible
sudo ansible-galaxy install geerlingguy.homebrew
```

# Run:
ansible-playbook -v site.yml --ask-become-pass --extra-vars "user=$USER"

