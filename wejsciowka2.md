1. czy należy
2. czy zawiera
3. ile ujemnych

```py
lista1 = [1,3,5,7,-2,]
lista2 = [1,5]
element = 7

def czy_należy(lista,ele):
    for x in lista:
        if ele == x:
            return True

    return False

def czy_zawiera(lista1,lista2,element):
    for e in lista2:
        if not czy_należy(lista1,e):
            return False
    return True
def ile_ujemnych(lista):
    ile_uj = 0
    for x in lista:
        if x < 0:
            ile_uj +=1

    return ile_uj

print(czy_należy(lista2,element))
print(czy_zawiera(lista1,lista2,element))
print(ile_ujemnych(lista1))
```
