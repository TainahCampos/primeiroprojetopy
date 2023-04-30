# primeiroprojetopy
um dos meus primeiros exercícios em python




nota1 = int (input ('Qual nota da primeira prova?'))
nota2 = int (input ('Qual nota da segunda prova?'))
nota3 = int (input ('qual a nota da terceira prova?'))
mediadenotas =   (nota1 + nota2 + nota3)/ 3
notatotal = (nota1 + nota2 + nota3)
compeso = ((nota1* 2) + ( nota2 * 2 ) + ( nota3*3)) /7

print (f'A media simples é', {mediadenotas})
print (f'o total de pontos foi de ' , {notatotal})
print (f'oOtotal da média considerando os pesos aplicados é de' , {compeso})

if compeso >= 7:
  print ("APROVADO")
elif compeso  >= 5:
  print ("prova final")

else:
  print('REPROVADO')


num1 = int(input ('Digite um numero'))
num1_1 =num1 - 1
num1_2 = num1 +1
print ('o antecessor de', {num1} , 'é', {num1_1} , ' e seu sucessor é', {num1_2})

num2 =int(input('Digite um numero'))
num2_1 = num2 *2
num2_2 = num2 *3
num2_3 = num2**2
print ( 'o dobro de', {num2} , "é", {num2_1}, ' o triplo é ', {num2_2}, ' e sua raiz quadrada é', {num2_3} )

metros = int(input ('quantos metros tem seu quarto?'))
metros1= metros *100
metros2 = metros *1000
print ("seu quarto tem ", {metros1}, ' centimetros e', {metros2} , "milimetros")


