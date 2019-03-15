##### La théorie des ensembles (Sets)

* Opérations sur les ensembles

```python
# Intersection de deux ensembles A et B 
# l’ensemble des éléments qui appartiennent à la fois à A et B
print(a & b)
{'a', 'c'}

# Différence de deux ensembles A et B 
# l’ensemble des éléments qui appartiennent à A mais pas à B
print(a - b )
{'r', 'd', 'b'}

# Différence symétrique de A et B
# l’ensemble des éléments qui appartiennent à A ou à B 
# mais pas aux deux à la fois
print(a ^ b)
{'r', 'd', 'b', 'm', 'z', 'l'}

# Réunion de deux ensembles A et B 
# l’ensemble des éléments qui appartiennent à A ou à B 
# (éventuellement les deux)
print(a | b )
{'a', 'c', 'r', 'd', 'b', 'm', 'z', 'l'}
```
