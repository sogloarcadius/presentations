##### Roles

roles -- vlan -- tasks -- main.yml

```yaml
- name : Configure VLAN
  ios_vlan:
    vlan_id: 100
```

roles -- ntp -- tasks -- main.yml

```yaml
- name : Configure ntp
  ios_config:
    lines: ntp server 1.2.3.4
```