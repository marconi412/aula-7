# aula-7
atvd 1
condicao1= (input("sol"))
condicao2= (input("dinheiro"))

if (condicao1 and condicao2):
    print("deu praia")
else:
    print("liso dorme")

atvd 2
carro= int (input ("ano do carro"))
preco= float (input ("preço do carro"))
if(carro < 1990):
    print ("voce pagara:", preco * 0.01)
else:
    print ("voce pagara", preco * 0.015 )

atvd 3
#ler o salario e o cargo
#calcular o aumento
salario= int (input("seu salario"))
cargo= int (input("codigo de cargo"))
if (cargo== 101):
    print ("seu salario era", salario, "ira para", salario * 1.10, "aumento de:", salario * 1.10- salario)
elif (cargo== 102):
    print ("seu salario era", salario, "ira para", salario * 1.20, "aumento de:", salario * 1.20- salario)
elif (cargo== 103):
    print ("seu salario era", salario, "ira para", salario * 1.30, "aumento de:", salario * 1.30- salario)
else: 
    print ("seu salario era", salario, "ira para", salario * 1.40, "aumento de:", salario *1.40- salario)
