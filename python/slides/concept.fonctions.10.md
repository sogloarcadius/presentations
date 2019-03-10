
![](resources/python.libs.3.png)

```py
import os
print(os.uname())
print("The current working directory is %s" %(os.getcwd()))
print("The current working directory is %s" %(os.path.realpath(os.path.dirname(__name__))))
os.environ["TOKEN"] = "xxtoken"
print(os.getenv("TOKEN"))
print(os.environ)
print(os.environ.get("TOKEN"))
```