##### Inventory

*inventory.yml*

```yaml
routers:
    children:
        junos:
            hosts:
                vsrx01:
                    ansible_host: 172.16.1.1
                vsrx02:
                    ansible_host: 172.17.1.1
        ios:
            hosts:
                ios01:
                    ansible_host: an-ios-01.rhdemo.io
```