##### YAML

Dictionnaire

```yaml
a_nested_map:
  key: value
  another_key: Another Value
  another_nested_map:
    hello: hello
```

Liste / Sequence

```yaml
a_sequence:
  - Item 2
  - 0.5
  - key: value
    another_key: another_value
```

Anchors

```yaml
base: &base
  name: Everyone has same name

foo: &foo
  <<: *base
  age: 10
```