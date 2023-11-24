# Zadanie 1

### a
```py
n = 7

def dzielniki(liczba):
    wynik = []
    for i in range(1,liczba):
        if liczba % i == 0:
            wynik.append(i)
    return wynik

print(dzielniki(n))

def liczba_pierwsza(liczba):
    dz = dzielniki(liczba)
    if dz == [1]:
        return liczba

print(liczba_pierwsza(7))

def liczbypd(liczba):
    wynik = []
    for i in range(liczba):
        if liczba_pierwsza(i) != None:
            wynik.append(i)
    return wynik
print(liczbypd(100))
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
n = 100

def dzielniki(liczba):
    wynik = []
    for i in range(1,liczba):
        if liczba % i == 0:
            wynik.append(i)
    return wynik

def liczba_pierwsza(liczba):
    dz = dzielniki(liczba)
    if dz == [1]:
        return liczba


def dziel_pier(liczba):
    dz = dzielniki(liczba)
    wynik = []
    for n in dz:
        if liczba_pierwsza(n) != None:
            wynik.append(n)
    return wynik

print(dzielniki(n))
print(dziel_pier(n))

```
##  d
```py
n = 1000

def ciomgdo(liczba):
    i = 0
    temp = 1
    wynik = []
    while i <= liczba:
        temp += i
        wynik.append(temp)
        i += temp
        wynik.append(i)
    return wynik

print(ciomgdo(1000))

def bigfib(n)
    n = 



















```





















