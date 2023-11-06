## problem 1
```python
all = input("Give Input: ")
a = all.split(",")
print(a)
c = 50
h = 30
b=[]
for d in a :
    q = int(((2*c*int(d))/h)**.5)
    b.append(q)
    
print(b)
```

### output
    Give Input: 100,150,180
    ['100', '150', '180']
    [18, 22, 24]
