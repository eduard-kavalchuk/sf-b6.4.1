Before you run a playbook create a VM and specify its external IP address in ``hosts`` file.  

Run playbook (with a verbose output):
```
ansible-playbook -i hosts <file> -vv
```
Check a yaml file with linters:
```
yamllint <file>
```
Another way to check syntax:
```
ansible-playbook --syntax-check <file>
```
Execute Ansible playbook with requesting a password for a vault:
```
ansible-playbook --ask-vault-pass -i hosts <file>
```
Execute with tags:
```
ansible-playbook --tags "<tag name>" -i hosts postfix.yaml -vv
```
