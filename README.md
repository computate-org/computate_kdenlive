
# Install the kdenlive ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_kdenlive

# Clone the kdenlive ansible role. 
git clone git@github.com:computate-org/computate_kdenlive.git ~/.ansible/roles/computate.computate_kdenlive
```

# Run the kdenlive ansible playbook to install kdenlive locally. 

```bash
ansible-playbook ~/.ansible/roles/computate.computate_kdenlive/install.yml -K
```

