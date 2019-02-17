##### Ansible CLI

```sh
ansible localhost -m setup
```

Collecte d'informations avec le module **setup**

```sh
ansible ce1 -m raw -a 'show version'
```

Récupérer la version d'un routeur avec le module **raw**

