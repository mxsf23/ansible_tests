## Descrition

Just simple ansible role example. It will deploy vsftpd service with the given config.

You may use group_vars from repo or your own.
Fill out hosts.yaml with proper IP-address of the target host.

### Run playbok

``````
ansible-playbook vsftpd-playbook.yaml --vault-password-file psswd_file -i hosts.yaml
``````
