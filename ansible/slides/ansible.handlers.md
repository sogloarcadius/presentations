##### Handlers

Task qui s'éxécute suite à un évenement

```yaml
tasks:
- name: httpd package is present
  yum:
    name: httpd
    state: latest
  notify: restart httpd

handlers:
- name: restart httpd
  service:
    name: httpd
```

