# ansible-tools
compilation of usefull ansible roles, tasks, and playbooks 

# initial commands
```
$ ansible-playbook -i inventory-private.yml setup_server_playbook.yml --ssh-extra-args="-o PubkeyAuthentication=no" -k -K
```
