# Taxonomies
Taxonomies are used to create relations between projects. Each taxonomy type has its own file. Taxonomy files should be formatted either as an array of strings or as an object with the identifier of the taxonomy as the key and relevant data as the value.

Example taxonomy `colors.yaml`:
```yaml
- Green
- Red
- Blue
```

Example taxonomy `persons.yaml`:
```yaml
jane_doe:
- first_name: Jane
- last_name: Doe

john_doe:
- first_name: John
- last_name: Doe
```

---

Taxonomies should be self-explanatory meaning that the yaml files themselves should include enough information to be understandable by a human being.
