# smokeping-ansible
Ansible playbook for setting up a smokeping VM


# Setup prerequisites

## Install Python/pip

## Install Ansible
```
pip install ansible
```

## Copy/Edit Targets example
In roles/docker-compose/templates is a Targets.example you need to copy
```
cp roles/docker-compose/templates/Targets{.example,}
```
Now modify and replace what you will need for your homelab in that example.

# Run

## Apply playbook with the following:
```
ansible-playbook app.yml --ask-become-pass
```
