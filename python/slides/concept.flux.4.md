##### Context Manager **with**

```python

with open("/etc/passwd") as fp:
    content = fp.read()
    print(content)
```