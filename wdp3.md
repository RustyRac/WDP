# Zadanie 1
```py
napis = 'abababababra'
usuwany = 'ab'
def remove(napis,usuwany):
    for i in range(len(napis)):
        if napis[i] == usuwany[0]:
            end = i + len(usuwany)
            temp = napis[i:end]
            if usuwany == temp:
                return napis[:i] + napis[end:]
                
    return napis
    
print(remove(napis,usuwany))
```
# Zadanie 2
```py
def remove_all(napis, usuwany):
    i = 0
    while i <= len(napis):
        napis = remove(napis,usuwany)
        
        i += 1
    return napis
    
print(remove_all(napis,usuwany))
```
# Zadanie 3
```py
import numpy as np
dlg = 6
lista = []
min = -3
max = 7
def generuj(dlg, min, max):
    for i in range (0, dlg):
        lista.append(random.randint(min,max + 1))
        
print(generuj(dlg,min,max))
```
