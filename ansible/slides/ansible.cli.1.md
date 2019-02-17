##### Ansible CLI

```sh
ansible all -m ping
```

Vérifier la connectivité des machines avec le module **ping**
Le module ping ne fonctionne pas sur les équipements réseaux


Parametre | Explication
------------ | -------------
ansible | L'executable d'ansible
all | execute la commande sur tous les host dans inventory
-m ping | spécifier le module à executer