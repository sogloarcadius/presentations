
![](resources/python.libs.5.png)

```py
import json

# Lire un fichier json
with open('person.json') as jsonfile:
  python_dict = json.load(jsonfile) # file,stream,...
  #python_dict = json.loads(jsonfile.read())  

person_dict = {"name": "Arcadius", "age": 24, "city": "Rennes"}

person_string = '{"name": "Arcadius", "age": 24, "city": "Rennes"}'

# Ecrire dans un fichier json
with open('person.json', 'w') as json_file:
  #json.dump(person_string, json_file)
  json.dump(person_dict, json_file)

```