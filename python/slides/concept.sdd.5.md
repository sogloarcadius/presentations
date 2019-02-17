##### Les dictionnaires

* Accéder à des éléments du dictionnaire

```python
print(dico['mouse']) # afficher un élément spécifique

# afficher tous les éléments
for key,value in dico.items():
    print("%s : %s" %(key : value))
```

* Ajouter un élément au dico

```python
dico["pineapple"] = "ananas"
dico["apple"] = "pomme"
```
* Supprimer un élément du dico

```python
del(dico["pomme"])
```

