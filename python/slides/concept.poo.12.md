##### Héritage multiple

* [Diamond Problem](https://en.wikipedia.org/wiki/Multiple_inheritance)

```py
class UnObjet:
    nom = None
```

```py
class Vehicule(UnObjet):
    nombre_roue = 4
```

```py
class Voiture(Vehicule):
    nombre_porte = 4
```

```py
class VoitureSport(Voiture):
    couleur = 'rouge'
```

```py
class Renault(Voiture):
    nom = 'renault'
```

```py
class Ferrari(Voiture, VoitureSport):
    nom = 'ferrari'
```

