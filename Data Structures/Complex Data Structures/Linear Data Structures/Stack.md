### Stack
It is a linear data structure which facilitates the concept of LIFO (last in first out)/ FILO (First in last out).

#### Insertion of data
Push

#### Deletion of Data
Pop

#### Peak
The top element of the stack. (last inserted element)
```python 3
l = len(a) -1
peak = a[l]
```

#### Underflow
When we dont have any elements in our stack, its in a state of underflow when we perform a pop.

#### Overflow
Happens when we try to append over array size.
Not in Python

#### Display All
will display all the elements of the stack, with the last inserted element of the stack being displayed first.

```python 3
for i in range(len(a)-1, -1, -1):
	print(a[i])
```
