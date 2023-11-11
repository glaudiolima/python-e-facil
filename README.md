# python-e-facil
def saudacao(nome):
  print(f"Olá {nome}, Seja bem vindo")
nome = input("digite seu nome: ")
saudacao(nome)
data = input("digite a data de nascimento: ")
idade = 2023 - int(data)
print(f"você tem {idade} anos") 
