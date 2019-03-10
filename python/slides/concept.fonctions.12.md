
![](resources/python.libs.5.png)

```py
import json

person_dict = {
  "name": "Arcadius",
  "age": 24,
  "city": "Rennes"
}

# prend un json/dict et retourne une chaine de caractere
person_string = json.dumps(person_dict)

# prend une chaine de charactere et retourne un json/dict
person_string = '{"name": "Arcadius", "age": 24, "city": "Rennes"}'
python_dict = json.loads(person_string)
```