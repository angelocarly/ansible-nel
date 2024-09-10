# Nel.re ansible

## Commands

Following [this](https://docs.ansible.com/ansible/latest/getting_started/get_started_inventory.html)

- Verify the hosts
  - `ansible-inventory -i inventory.ini --list`
- Ping the `myhosts` group
  - `ansible myhosts -m ping -i inventory.ini -u root`
- Run a playbook
  - `ansible-playbook -i inventory.ini playbook/users.yaml`
