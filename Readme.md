# Carlo's Ansible playbooks

1. `sudo apt install ansible`
1. `ansible-galaxy install -r requirements/common.yml`
1. `sudo whoami`
1. `ansible-playbook main.yml --ask-become-pass`

## Run single role
`ansible-playbook main.yml --tags zsh,codium,firefox`