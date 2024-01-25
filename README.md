## Descrition

Just simple test with vault and tags. Nothing special.

You may use group_vars from repo or your own.
Fill out hosts.yaml with proper IP-address of the target host.

### Run playbok

``````
ansible-playbook user_tags.yaml --vault-password-file psswd_file -i hosts.yaml // Create a new user and puts ssh-key from vault into user's homedir.

ansible-playbook user_tags.yaml --vault-password-file psswd_file -i hosts.yaml --tags="init postfix" // Install Postfix

ansible-playbook user_tags.yaml --vault-password-file psswd_file -i hosts.yaml --tags="drop postfix" // Remove Postfix
``````