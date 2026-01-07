###Variables
- dont need to declare types
- types are declared at runtime
```
#variables are dynamically typed
n = 0
print('n = ', n)

n = 'abc'
print('n = ', n)
 
#Multiple assignments
n, m, o = 'a', 2, False
  
#Increment
m = m +1
m += 1
print(m)

#Null value
n = None
print( 'n = ', n)
```

###If Statements
- parentheses is needed for multi-line conditions 
-  and = &&
- or = ||

```
#if statements
n = 1
if n > 2:
    n -=1 
elif n == 2:
    n *= 2
else: 
    n += 2

print (n)

#parentheses for multi line conditions
n, m = 1, 2
if ((n > 2 and n != m) or n == m):
    n += 1

print ( 'n =', n)
```

###For and while loops
###Math funcs
###Arrays
- Called lists in python
- dynamic arrays by default
- can be used as stack
- Unlike pushing and popping an array, inserting a value in the middle is a big O of n time operation
- To index an array is constant time operation
- Similar to for-loop ranges, last index is non inclusive as well

###Sorting
lambda, function without a name

###list comprehension
- newlist = expression for item in iterable if condition == True