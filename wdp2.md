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
# Zadanie 3
```python

print('Zadanie 3')
lista = [0, 1, 2, 3, 4, -5, -6, 7, -8, -9]

def ile_ujemnych(lis):
    ujemne = 0
    for x in lis:
        if x < 0:
            ujemne += 1
    return ujemne

print(lista)
print(ile_ujemnych(lista))
```
# Zadanie 4

```python
print('Zadanie 4')
lista = [2, 3, 1, 3]

def iloczyn(lis):
    iloczyn = 1
    for x in lis:
        iloczyn = iloczyn * x
    return iloczyn

print(lista)
print(iloczyn(lista))
```

# Zadanie 5

```python
print('Zadanie 5')
lista = [31, 28, 31, 30, 31, 30, 31, 31, 30, 31, 30, 31]

def minmax(lis):
    krotka = (min(lis), max(lis))
    return krotka

print(lista)
print(minmax(lista))
```

# Zadanie 6

```python
print('Zadanie 6')
lista = [5, 3, 1, 4, 2]

def czy_nalezy(lis, ele):
    naleznosc = False
    for x in lis:
        if x == ele:
            naleznosc = True
            break
        else:
            naleznosc = False
    return naleznosc

print(lista)
print(czy_nalezy(lista, 1))
```

# Zadanie 7
```python
print('Zadanie 7')
lista1 = [5, 3, 1, 4, 2]
lista2 = [1, 3]

def czy_zawiera(lis1, lis2):
    ile_zawiera = 0
    for x2 in lis2:
        for x1 in lis1:
            if x2 == x1:
                ile_zawiera += 1
                break
    if ile_zawiera == len(lis2):
        return True
    else:
        return False

print(lista1)
print(lista2)
print(czy_zawiera(lista1, lista2))
```
