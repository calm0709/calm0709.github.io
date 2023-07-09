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
---
split string
---
```
# split text by length
def wrap(string, max_width):
    return textwrap.fill(string,max_width)
```
---
set(중복 없음)
---
```
s1 = set([1,2,3])
print(s1)                # {1,2,3}

s2 = set(4,5,6)
print(s2)               # TypeError: set expected at most 1 arguments, got 3

```
