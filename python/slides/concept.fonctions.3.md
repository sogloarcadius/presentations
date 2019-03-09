##### Définir une fonction

```py
# Volume d'un sphere

def cube(nombre):
    """docstring : Ceci est un commentaire 
    """
    return nombre**3

def volumeSphere(rayon):
    """retourne le volume d'un sphere de rayon 
        v = (4 * pi * r**3) / 3
    """
    return 4 * 3.1416 * cube(rayon) / 3
```