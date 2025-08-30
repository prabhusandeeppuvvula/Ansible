# Ansible

# Installing ansible

sudo apt update -y

sudo apt install ansible -y

ansible --version

# Create Playbook to Install Packages

nano install_packages.yml

Paste the ansible code.

# Run the Playbook
ansible-playbook -i hosts.ini install_packages.yml
