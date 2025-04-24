# Projeto - Cálculo de Salário com Comissão de Vendas

Este projeto em Java calcula o salário total de um trabalhador com salário fixo e comissão sobre vendas. O trabalhador recebe um valor fixo de salário mais uma comissão baseada no valor das vendas realizadas no mês. Se as vendas forem inferiores a R$1500, ele receberá uma comissão de 3%. Caso as vendas superem esse valor, ele receberá uma comissão de 3% sobre as primeiras R$1500 e 5% sobre o valor que exceder esse limite.

## Funcionalidade

O programa solicita que o usuário insira:
1. O salário fixo do trabalhador.
2. O valor total das vendas realizadas no mês.

O programa então calcula o salário total, considerando:
- Uma comissão de 3% sobre o valor das vendas até R$1500.
- Uma comissão de 5% sobre o valor das vendas que ultrapassarem R$1500.

### Exemplo:

- Se o trabalhador tem um salário fixo de R$ 1.200 e realizou vendas no valor de R$ 2.000:
  - Para os primeiros R$ 1.500 de vendas: 1.500 * 3% = R$ 45.
  - Para o restante (R$ 500): 500 * 5% = R$ 25.
  - O salário total será: R$ 1.200 + R$ 45 + R$ 25 = R$ 1.270.

## Como Funciona

1. O programa solicita o salário fixo e o valor das vendas.
2. O programa calcula a comissão com base no valor das vendas:
   - Para vendas até R$ 1.500, a comissão é de 3%.
   - Para vendas superiores a R$ 1.500, a comissão sobre o excedente é de 5%.
3. O salário total é calculado e exibido.

  ```bash
   Digite o seu salario: 1200
Digite o valor das vendas: 2000
O seu salario total e de R$1270.0
