# PYTHONCODES
PYTHON PROGRAMS

import math

a = float(input("Enter a: "))
b = float(input("Enter b: "))
c = float(input("Enter c: "))

d = b*b - 4*a*c   # discriminant

if d > 0:
    root1 = (-b + math.sqrt(d)) / (2*a)
    root2 = (-b - math.sqrt(d)) / (2*a)
    print("Real and distinct roots:", root1, root2)
elif d == 0:
    root = -b / (2*a)
    print("Real and equal roots:", root)


2.PRIME NUMBER QUESTION:

n = int(input("Enter a number: "))
flag = True

if n < 2:
    flag = False
else:
    for i in range(2, n):
        if n % i == 0:
            flag = False
            break

if flag:
    print("Prime number")
else:
    print("Not a prime number")
n = int(input("Enter n: "))

b)for num in range(2, n+1):
    isprime = True
    for i in range(2, num):
        if num % i == 0:
            isprime = False
            break
    if isprime:
        print(num, end=" ")

c)n = int(input("Enter how many primes: "))
count = 0
num = 2

while count < n:
    for i in range(2, num):
        if num % i == 0:
            break
    else:
        print(num, end=" ")
        count += 1
    num += 1
        



    
else:
    print("Imaginary roots")
