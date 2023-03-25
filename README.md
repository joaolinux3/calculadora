# calculadora
#calculadora python

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y
#definir parametro

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        raise ValueError('Não pode dividir por zero burro!')
    return x / y

print("Selecione qualquer coisa")
print("1-somar")
print("2-diminuir")
print("3-Multiplicar")
print("4-Dividir")

calculadorajoao = input("Digite o oque vc quer: (1/2/3/4): ")

calcular01 = int(input("Digite o primeiro número: "))
Calcular02 = int(input("Digite o segundo número: "))

if calculadorajoao == '1':
    print(calcular01,"+",Calcular02,"=", add(calcular01,Calcular02))

elif calculadorajoao == '2':
    print(calcular01,"-",Calcular02,"=", subtract(calcular01,Calcular02))

elif calculadorajoao == '3':
    print(calcular01,"*",Calcular02,"=", multiply(calcular01,Calcular02))

elif calculadorajoao == '4':
    print(calcular01,"/",Calcular02,"=", divide(calcular01,Calcular02))
else:
    print("N deu pra você entrar animal")

""""
  Projeto Feito por joao
Calculadora simples em Python
Sem usar nenhuma Biblioteca
espero que goste :)


"""
