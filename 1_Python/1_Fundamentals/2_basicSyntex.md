# Basic Sytax
## IF
```
a = 15
if a < 5:
    print('a < 5')
elif a < 10:
    print('5 <= a < 10')
else:
    print('a >= 10')
```
## 2. Funtions
```
def func_2(a, b):
    return a * b

func_2('a', 3)
func_2(2, 3)

or
def func_3(a: int, b:int):
    return a * b
```
### 2b. Lambda: The **lambda** keyword, that also creates a new function, but does not assign it to any specific name 
```
func_5 = lambda x: x**2
func_5(2)
```

## 3. While Loop 
```
i = 0
while i < 5:
    print(i)
    i += 1

     i = 5

while True:
    print(i)
    if i >= 5:
        break

a = 0
while a < 10:
    a += 1
    if a % 2:
        continue
    print(a)
```
### 3b. User input with while loop:
```
min_length = 2
name = input('Please enter your name:')
while not(len(name) >= min_length  and name.isprintable() and name.isalpha()):
    name = input('Please enter your name:')

print('Hello, {0}'.format(name))
```

### 3b. Traversing a list with while loop:
```
l = [1, 2, 3]
val = 10

found = False
idx = 0
while idx < len(l):
    if l[idx] == val:
        found = True
        break
    idx += 1
    
if not found:
    l.append(val)
print(l)
```

## 4. For Loop: 
```
for (int i=0; i < 5; i++) {
    //code block
}

for i in range(5):
    print(i)

List:
for x in [1, 2, 3]:
    print(x)

String: 
for x in 'hello':
    print(x)

Tuple: 
for x in ('a', 'b', 'c'):
    print(x)

List of Tuples: 
for x in [(1, 2), (3, 4), (5, 6)]:
    print(x)
or
for i, j in [(1, 2), (3, 4), (5, 6)]:
    print(i, j)

```
### 4b. Try Catch with For loop:
```
for i in range(5):
    print('--------------------')
    try:
        10 / (i - 3)
    except ZeroDivisionError:
        print('divided by 0')
        continue
    finally:
        print('always runs')
    print(i)
```
    
