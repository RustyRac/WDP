# Zadanie 1
```py
d = {}
d = {5:3, 8:4}
print(d)
print(d[5])
lista = [8,5,8,2,5,3,8,7]
zdanie = 'tak jak najbardziej'

def czy_nalezy(x,lista):
    for i in lista:
        if i == x:
            return True
    return False

def unikalne(lis):
    wynik = []
    for i in lis:
        if not czy_nalezy(i,wynik):
            wynik.append(i)
    return wynik

print(unikalne(zdanie))

def czestosc(lista):
    wynik = {}
    for e in lista:
        if not czy_nalezy(e,wynik):
            wynik[e] = 1
        else:
            wynik[e] += 1
    return wynik

print(czestosc(lista))
```

# Zadanie 2

```py
d = {}
d = {5:3, 8:4}
print(d)
print(d[5])
lista = [8,5,8,2,5,3,8,7]
zdanie = 'tak jak najbardziej'

def czy_nalezy(x,lista):
    for i in lista:
        if i == x:
            return True
    return False

def unikalne(lis):
    wynik = []
    for i in lis:
        if not czy_nalezy(i,wynik):
            wynik.append(i)
    return wynik

print(unikalne(zdanie))

def czestosc(lista):
    wynik = {}
    for e in lista:
        if not czy_nalezy(e,wynik):
            wynik[e] = 1
        else:
            wynik[e] += 1
    return wynik

print(czestosc(lista))

def idk(d):
    wynik = {}
    for k in d:
        if k >= 'a' and k <= 'z':
            wynik[k] = d[k]
    return wynik

print(idk(czestosc(zdanie)))


```
