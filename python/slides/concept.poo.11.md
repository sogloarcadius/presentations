##### Héritage

```py

class Mammifere(object):
    caract1 = "il allaite ses petits ;"

class Carnivore(Mammifere):
    caract2 = "il se nourrit de la chair de ses proies ;"

class Chien(Carnivore):
    caract3 = "son cri s'appelle aboiement ;"


mirza = Chien()
print(mirza.caract1, mirza.caract2, mirza.caract3)
```
