## Lists
```
cars = ['a', 'b', 'c', 'd']

# add to end of list.
cars.append('c')

# remove from end of list. takes an optional index.
lastcar = cars.pop([i])

# insert into list. any integer for index is possible. 
# this performs an insert not a replacement.
cars.insert(0,'x') -> None

# returns the number of times x is found in the list. 
cars.count('a')

# sort the list in place.
cars.sort() -> None

# shallow copy of a list 
cars_copy = cars[:]

```
Lists can be used as a stack using `stack.append(val)`, `stack.pop()` and `stack[-1]`

## Tuple 
```
cars = 'a', 'b' , 'c' 

# creating an empty tuple
cars = () 

#tuple with one element
cars = 'a',

# tuples in immutable, but can container mutable objects. 
cars[0] = 'x' # error out. 
```

Strings, Lists and Tuples are `Sequence Types`. Sequence Types can undergo `Sequence Unpacking`. Sequence Types can be unpacked as follows:
` x, y, z = t`

## Sets
```
x = set() 
x = {'a', 'b', 'c'}
x = set('abcdefg')

# membership test
'a' in x 

# set operations 
x = set()
y = set() 

x - y # items in x but not in y. 
x | y # items in x or y or both. 
x & y # items in x and y 
x ^ y # items in x or y but not both. 
```

## Dictionary 
Dictionary is of type Mapping. 

It is an error to extract a value w/ a non existent key. 

```
x = {'jack': 5, 'jill': 2} 
del x['jack'] 
keys = list(x) 
print(keys) # ['jill']

'jill' in x # true
'jill' not in x # false

```

Dictionary Looping
```
for k, v in x.items():
  print(k, v)
```



