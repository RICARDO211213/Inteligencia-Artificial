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

Codigo C++

#include <iostream>
#include <cstdlib>

using namespace std;

int main()
{
	int posicion [10];
	int x;

	posicion [0] = 0;
	posicion [1] = 1;

	cout << "Codigo de Fibonacci 10\n";
	cout << posicion[0] << endl << posicion[1] << endl;

	for(x = 2 ; x <= 9; x++)

	{
		posicion[x] = posicion[x - 1] + posicion[x - 2];
		cout << posicion[x] << endl;
	}

	system("pause");
	return 0;
}
