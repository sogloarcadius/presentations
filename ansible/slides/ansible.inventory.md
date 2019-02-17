##### Inventory

* Collection de machine et groupe de machine

*inventory.ini*

```ini
[junos]
vsrx01 ansible_host=an-vsrx-01.rhdemo.io private_ip=172.16.1.1
vsrx02 ansible_host=an-vsrx-02.rhdemo.io private_ip=172.17.1.1

[junos:vars]
ansible_network_os=junos
ansible_password=Ansible

[ios]
ios01 ansible_host=an-ios-01.rhdemo.io

[ios:vars]
ansible_network_os=ios
ansible_become=yes
ansible_become_method=enable
ansible_become_pass=cisco
```