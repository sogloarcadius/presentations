##### La méthode constructeur

```py
class Time(object):
    "Encore une nouvelle classe temporelle"
    def __init__(self, hh=12, mm=0, ss=0):
        self.heure = hh
        self.minute = mm
        self.seconde = ss
    def affiche_heure(self):
        print("{0}:{1}:{2}".format(self.heure, self.minute, self.seconde))


recreation = Time(10, 15, 18)
recreation.affiche_heure()
```
