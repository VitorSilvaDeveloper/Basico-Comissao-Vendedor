from time import sleep

nome = str(input('Qual o nome do vendedor?'))
salario = float(input('Qual o seu salário base? R$'))
comissao = int(input('{} Fez quanto em vendas R$?'.format(nome)))

print('Calculando...')
sleep (1)
print('Validando...')
sleep(1)

inss = salario - (salario * 8/ 100)
passagem = inss - (inss * 6 / 100)
valor_final = passagem
valor_comissao = comissao * 15/100
salario_final = valor_final + valor_comissao

print('O salário bruto é de R${:.2f}'.format(salario))

print('O salário liquído é de R${:.2f}'.format(valor_final))

print('O vendedor fez {} em vendas, e ganha 15% de comissão pelo total de vendas!'.format(comissao))

print('Valor da comissão é de R${:.2f}'.format(valor_comissao))

print('valor a pagar para {} é de R${:.2f}'.format(nome, salario_final))

if comissao >= 1200:
    resultado =  comissao * 10 / 100
    resultado2 = resultado + salario_final
    print('{}, vendeu mais de R$1.200 e por isso ganha um bonus a mais de 10% e assim ganha no total R${:.2f}'.format(nome, resultado2))

print('BOAS VENDAS!')
