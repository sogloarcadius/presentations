##### YAML

Enumération

```yaml
set:
  ? item1
  ? item2
  ? item3

set2: {item1, item2, item3}
```

| 
Conserve les sauts de ligne et tabs

```yaml
literal_block: |
    This entire block of text will be the value of the 'literal_block' key,
    with line breaks being preserved.
```

\> 
Ne conserve pas les sauts de ligne

```yaml
folded_style: >
    This entire block of text will be the value of 'folded_style', but this
    time, all newlines will be replaced with a single space.
```