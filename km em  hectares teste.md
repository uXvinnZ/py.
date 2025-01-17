import time
#Aviso
print(""""[1] km em hectares
 [2] hectares em km""")
time.sleep(1)

#Pergunta de Entrada
r = float(input("Digite a opcao: "))

#estrutura de decisao
if r == 1:
    r1 = float(input("Digite o numero: "))
    r2 = (r1 * 100)
    print(f"{r1} em hectares sao {r2}")
elif r == 2:
    r1 = float(input("Digite o numero: "))
    r2  = (r1 / 100)
    print(f"{r1} em k sao {r2}")
