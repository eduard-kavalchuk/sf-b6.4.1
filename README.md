Before you run a playbook create a VM and specify its external IP address in ``hosts`` file.
Run playbook (with a verbose output):
```
ansible-playbook -i hosts <file> -vv
```
Check a yaml file with linters:
```
yamllint <file>
```
