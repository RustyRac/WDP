# Zad 4
```py
# -34
def zad(sciezka):
    slownik = {}
    with open(sciezka, "r") as plik:
        for linia in plik:
            elementy = linia.split()
            for element in elementy:
                try:
                    liczba = int(element)
                    if liczba in slownik:
                        slownik[liczba] += 1
                    else:
                        slownik[liczba] = 1
                except:
                    pass
    return slownik


print(zad('wejsciowka.py'))
```
