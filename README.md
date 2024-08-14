# Jump host with variables

### Ansible playbook structure:

```
ansible-jump-host/
  ansible.cfg
  inventory
    hosts
  ssh.cfg
```


```bash
ansible app_servers -i inventory -u ubuntu -m ping
```
