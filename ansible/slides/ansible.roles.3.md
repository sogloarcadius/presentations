##### Roles

Playbook qui utilise les roles ntp et vlan.

```yaml
- hosts: routers
  roles:
    - ntp
    - vlan
```

Ansible exécute les tasks de **ntp** puis de **vlan**
