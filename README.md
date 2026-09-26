import random

caracteres = "+-/*!&$#?=@abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

tamanho = int(input("Digite o tamanho da senha: "))

senha = ""

for i in range(tamanho):
    senha = senha + random.choice(caracteres)

print("Senha gerada:", senha)

altura = 5
for i in range(1, altura + 1): print("*" * i)

nome = input("Digite um nome: ")

print("*" * (len(nome) + 2))
print("*" + nome + "*")
print("*" * (len(nome) + 2))

n = int(input("Digite um número: "))

soma = 0

for i in range(1, n + 1):
    soma = soma + i

print("A soma é:", soma)
