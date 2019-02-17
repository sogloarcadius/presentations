##### Playbook

* Collection de Tasks/Handlers
* Ansible exécute sequentiellement les tasks dans le playbook

*playbook.yml*

```yaml
- hosts: routers
  tasks:
    - name: test connection
      ios_ping:
        dest: 10.10.10.10
```