##### Fonctions de la librairie communautaire

Exemple : numpy

[https://docs.scipy.org/doc/numpy/reference/index.html](https://docs.scipy.org/doc/numpy/reference/index.html)

* Installation de la librairie

```sh
C:\> pip install numpy 
C:\> pip install numpy --index-url https://artifactory-iva.si.francetelecom.fr/artifactory/api/pypi/pythonproxy/simple
```

* Utilisation des fonctions de la librairie

```py
from numpy.random import rand
values = rand(10)
print(values)
```