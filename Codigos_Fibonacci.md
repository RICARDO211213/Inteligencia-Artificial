# Inteligencia-Artificial
IACIDE
Codigo Python 

print("Este Programa genera la sucesion de Fibonacci desde 10 posiciones ")

def fibonacci(n):
    if n == 1 or n == 0:
        return n
    else:
        return fibonacci(n - 1) + fibonacci (n - 2)
numero = int(input("Numero de valor Positivo"))
if numero < 0:
    print("Numero No Valido")
j = 0
print ("Sucesion de Fibonacci: ")
for j in range(0, numero):
    print(fibonacci(j))
