# Zadanie 1

### a
```py
n = 7
def dzielniki(x):
    dzielniki = []
    for n in range(1,x):
        if x % n == 0:
            dzielniki.append(n)
    return dzielniki
def pierwsza(n):
    dz = dzielniki(n)
    if dz == [1]:
        return n

print(pierwsza(3))

def wsz_pier(n):
    lista = []
    for i in range(n):
        if pierwsza(i) == i:
            lista.append(i)
    return lista

print(wsz_pier(100))
```
### b
```py
n = 10000
def dzielniki(x):
    dzielniki = []
    for n in range(1,x):
        if x % n == 0:
            dzielniki.append(n)
    return dzielniki

print(dzielniki(24))

def suma(lista):
    wynik = 0
    for liczba in lista:
        wynik += liczba
    return wynik

print(suma({1,2,3,4,8,12}))


def doskonala(liczba):
    dz = dzielniki(liczba)
    su = suma(dz)
    return su == liczba

print(doskonala(24))

def doskonale_n(n):
    lista = []
    for i in range(1,n):
        if doskonala(i) == True:
            lista.append(i)
    return lista

print(doskonale_n(n))
```
### c
```py


```
