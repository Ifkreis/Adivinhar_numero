import random as rd

cont = 0
numero_aleatorio = rd.randint(1,100)
numero = int(input('Digite um numero de 1 a 100: '))

while numero != numero_aleatorio:
    if numero < numero_aleatorio:
        print('Numero é maior')
        cont = cont + 1

    elif numero > numero_aleatorio:
        print('Numero é menor do digitado')
        cont = cont + 1

    numero = int(input('Digite um numero: '))
print(f'você acertou o numero escolhido foi {numero_aleatorio}')
print(f'o numero de tentativas foram {cont}')
