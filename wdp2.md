# Zadanie 1
```python
lista = []
for i in range(1,11):
    lista.append(i)
print(lista)
lista = []
for i in range(1,11):
    lista.append((i-1)*2)
print(lista)
lista = []
suma = 0
for i in range(1,21,2):
    suma += i
    lista.append(suma)
print(lista)
lista = []
for i in range(1,11):
    lista.append(i*0)
print(lista)
lista = []
for i in range(1,11):
    if i % 2 == 0:
        lista.append(1)
    else:
        lista.append(0)
print(lista)
lista = []
for i in range(1,3):
    for b in range(0,5):
        lista.append(b)
print(lista)
```

# Zadanie 2
```python
lista = []
i = 1
while i<=10:
    lista.append(i)
    i+=1
print(lista)

lista = []
i = 0
while i<=10:
    lista.append(i*2)
    i+=1
print(lista)

lista = []
i = 1
suma = 0
while i<=20:
    suma+=i
    lista.append(suma)
    i+=2
print(lista)

lista = []
i = 1
while i<=10:
    lista.append(0)
    i+=1
print(lista)

lista = []
i = 1
while i<=10:
    if i % 2 == 0:
        lista.append(1)
    else:
        lista.append(0)
    i+=1
print(lista)

lista = []
a=1
while a<=2:
    i = 0
    while i<=4:
        lista.append(i)
        i+=1
    a+=1
print(lista)
```
## Zadanie 3

