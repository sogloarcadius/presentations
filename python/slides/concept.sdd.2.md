##### Liste - Tableau - Array

[Les méthodes sur les listes](https://docs.python.org/3.7/tutorial/datastructures.html)

* Déclaration liste

```python
jour = ['lundi', 'mardi', 'mercredi', 'jeudi', 'vendredi']
```
* Taille d'une liste

```python
len(jour)
```
* Accéder à des éléments de la liste

```python
print(jour[0]) # premier élément
print(jour[0:3]) # trois premiers éléments
print(jour[-1]) # dernier élément
print(jour[-4:]) # quatre derniers éléments
```

* Ajouter élément à la liste

```python
jour.append('samedi')
```

* Supprimer élément de la liste

```python
del(jour[-1])
jour.remove("samedi")
```