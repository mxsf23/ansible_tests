## Descrition

Simple ansible example to create users, groups and add them to sudoers.

You may use group_vars from repo or your own.
Fill out hosts.yaml with proper IP-address of the target host.

### Run playbok

``````
ansible-playbook main-playbook.yaml --vault-password-file psswd_file -i hosts.yaml
``````
