##### Variables locales, variables globales

***global***

```py
>>> def plus_un():
        global a
        a = a+1
        print(a)

>>> a = 15
>>> plus_un()
16

>>> plus_un()
17
>>>
```