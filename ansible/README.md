## Run scripts on Raspberry

Check and fix mikrus ip
```
ansible-vault edit host_vars/mikrus.yml
```

Run ansible
```
ansible-playbook -i mikrus_inventory playbook.yml --ask-vault-pass
```
