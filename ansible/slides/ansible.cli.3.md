##### Ansible CLI

```bash
ansible-playbook -i iventory.yml playbook.yml -u username -k 
```

Parametre | Explication
------------ | -------------
ansible-playbook | L'executable d'ansible pour dérouler les playbooks
-i inventory.yml | Spécifier l'inventaire
playbook.yml | le chemin faire le playbook
-u username | specifier le nom d'utilisateur ssh
-k | demande la saisie du mot de passe