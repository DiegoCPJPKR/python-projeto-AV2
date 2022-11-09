NOME: DIEGO DE CASTRO PIMENTEL
MATRÍCULA: 202203252496

-------------ATIVIDADE – 5,0 NA AV2-------------
1)
BMa = int(input('Escreva a base maior: \n'))
BMe = int(input('Escreva a base menor: \n'))
Alt = int(input('Escreva a altura: \n'))

Area = (BMa + BMe) * Alt / 2

print(f'Resultado= {Area}')

-------------
2) 
def somaImposto(taxaImposto, custo):
    #cálculo do imposto.
    resultado_imposto = custo + (custo * taxaImposto / 100)
    #retorno do resultado do imposto
    return resultado_imposto

somaImposto(10, 45.00)
-------------
3) 
Mh = "A.M."
Td = "P.M."

def conversao(hora, minuto):
    if 0 <= hora <= 12 and 0 <= minuto < 60:
        return f"{hora}:{minuto} {Mh}"
    elif 12 < hora < 24 and 0 <= minuto < 60:
        return f"{hora - 12}:{minuto} {Td}"

def saida(hora, minuto):
    if hora > 23 or hora < 0:
        print("Hora inválida!")
    elif minuto > 59 or minuto < 0:
        print("Hora inválida!")
    else:
        print(f"{conversao(hora, minuto)}")

n = 1
while n != 0:
    hora = int(input("Hora: "))
    if hora < 0:
        break

    minuto = int(input("Minuto: "))

    saida(hora, minuto)
