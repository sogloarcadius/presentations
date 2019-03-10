
![](resources/python.libs.1.png)

```py
import re

# Use case de parsing du motd d'un équipement réseau
motd = " Programming in python is fun # no comment"
print(motd)
motd = re.sub(r'#.*', '', motd)
print(motd)

```