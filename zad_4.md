
import math

#a
def tabliczka_mnoz():
    n = int(input('Podaj n:'))
    temp = []
    if 0 < n < 100:
        for i in range(1, n+1):
            for j in range(1, n+1):
                temp.append(i*j)
            print(temp)
            temp = []
    else:
        print('n is too lagre')

print(tabliczka_mnoz())

#b

def nieskracalny():
    a = int(input('Podaj liczbę a:'))
    b = int(input('Podaj liczbę b:'))
    d = math.gcd(a,b)
    p = a//d
    q = b//d
    return p, q
print(nieskracalny())

#c

def matma():
    n = int(input('Podaj liczbę n:'))
    e1 = (1+1/n)**n
    e2 = 0
    for k in range(n+1):
        e2 += 1/math.factorial(k)

    return e1, e2

print(matma())


def NWD(a, b):
    while b:
        a, b =b, a % b
    return a
#d
print(NWD(10,20))



