# ContasBancarias
Projeto feito em java, utilizando os conceitos de programação orientada a objetos, encapsulamento, construtores, herança, polimorfismo e classes abstratas.
Proposta: 
Escreva um programa que gerencie transações relacionadas a contas em uma instituição
bancária.
Nessa instituição, há contas poupanças e contas correntes e, para cada conta bancária,
considere operações de saque e depósito. Quaisquer contas bancárias possuem número
(gerado sequencialmente) e saldo, mas apenas contas correntes possuem limite.
Portanto, operações de saque em contas correntes devem ser realizadas considerando-
se o valor do limite (saldo + limite), e operações de saque em contas poupanças devem
considerar apenas o valor do saldo.
As seguintes funcionalidades devem ser implementadas no código:
1) criar contas bancárias (armazenando-as em um array) com base em um valor de saldo
inicial;
2) efetuar saques e depósitos em uma conta bancária de acordo com o seu número.
Crie uma classe que permita gerenciar um array de contas bancárias de tal forma que
seu código seja desconectado de contas e transações específicas.
