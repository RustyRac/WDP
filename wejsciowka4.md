# czy należy czy zawiera czy doskonała
```py
lista1 = [1,2,3,4,5]
lista2 = [1,3]
ele = 4

def czy_nalezy(x,lista):
    for i in lista:
        if i == x:
            return True
    return False

print(czy_nalezy(ele,lista1))

def czy_zawiera(lista1,lista2):
    for x in lista2:
        if not czy_nalezy(x,lista1):
            return False
    return True

print(czy_zawiera(lista1,lista2))

def dzielniki(x):
    wynik = []
    for i in range(1,x):
        if x % i == 0:
            wynik.append(i)
    return wynik

print(dzielniki(12))

def czy_doskonala(x):
    dz = dzielniki(x)
    suma = 0
    for i in dz:
        suma += i
    if suma == x:
        return True
    else:
        return False

print(czy_doskonala(6))
```
