##### Variables locales, variables globales

* Les variables définies à l’extérieur d’une fonction sont des variables globales
* Les variables définies à l’intérieur d’une fonction sont des variables locales
* Les variables définies localement ont la priorité en cas de conflit(meme nom de variable)

```py

>>> def mask():
        p = 20
        print(p, q)

>>> p, q = 15, 38

>>> mask()
20 38

>>> print(p, q)
15 38
```