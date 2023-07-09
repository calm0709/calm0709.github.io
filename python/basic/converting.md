---
converting string to list, list to string
---

```
string = 'abc'
newString = ''
newList = list()

# string to list
lst = list(string)
print(lst)           # ['a', 'b', 'c']

# list to string
newList = ['a', 'b', 'c']
newString = ''.join(newList)
print(newString)           # abc
```
