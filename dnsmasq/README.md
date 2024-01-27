## Descrition

Ansible simple role for deploying dnsmasq server. 
See Defaults in role folder to check config variables applied to dnsmasq service by default.  

You may use group_vars from repo or your own.
Fill out hosts.yaml with proper IP-address of the target host.

### Run playbok

``````
ansible-playbook main-playbook.yaml --vault-password-file psswd_file -i hosts.yaml
``````
