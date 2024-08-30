# cheatsheet-python

[doc](https://docs.python.org/)

## Read a file

```python
with open("file.txt", "r", encoding='utf8') as file:
    for line in file:
        print(line)
```

## json

```python
import json

string = '{"name": "John", "age": 30, "city": "New York"}'
json_obj = json.loads(string)
print(json_obj)
```
