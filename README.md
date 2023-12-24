# -PY-A02-
par=[]
impar=[]
cont_par=0
cont_impar=0
lista=[]
tupla=()

for i in range(5):
    lista.append(int(input('Digite um valor: ')))

print (lista)
# separação de numeros pares dos impares
for x in lista:
    if x % 2==0:
        # acrecentando a uma lista e fazendo a contagem par!!
        par.append(x)
        cont_par+=1
        
    else:
        # acrecentando a uma lista e fazendo a contagem impar!!
        impar.append(x)
        cont_impar+=1
        
tupla= par,impar
     
print(f'Esses são os numeros "PAR": {par} numeros')
print(f'Esses são os numeros "IMPAR": {impar} numeros')
print(f' Essa é a tupla: {tupla}')
print(f' Contagem "PAR": {cont_par} numeros')
print(f' Contagem "IMPAR": {cont_impar} numeros')
print('A soma dos numeros "PAR"',sum (par))
print('A soma dos numeros "IMPAR"',sum (impar))
