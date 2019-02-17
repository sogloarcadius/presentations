##### Gestion des exceptions **try / except / finally / else**

```python

try:
    1/0
except Exception as exc :
    print ("erreur = {}".format(exc))
else:
    print ("else")
finally:
    print ("finally")
```