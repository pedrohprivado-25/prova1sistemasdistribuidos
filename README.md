# Prova 1 Sistemas Distribuídos

Nome: Pedro Henrique Privado Alves

RA: b75d38c11afddfb397a2

## Problema da Empresa

A empresa precisa de um programa que faça o cálculo do pagamento dos funcionários de acordo com as horas trabalhadas e o valor recebido por hora. 
O cálculo é feito pelo servidor e o cliente recebe o resultado.

## Arquivos
-servidor.py:recebe a chamada RPC e executa o cálculo.
-cliente.py:solicita o cálculo ao servidor e mostra a resposta.

## Resultado do Teste

PS C:\Users\Usuário\Documents\Prova> & C:\Users\Usuário\AppData\Local\Microsoft\WindowsApps\python3.13.exe c:/Users/Usuário/Documents/Prova/cliente.py
Valor do pagamento: 200
PS C:\Users\Usuário\Documents\Prova> 

## Explicação 

1.Em qual programa o Cálculo foi execultado?
R: O cálculo foi executado no servidor, na função calcular_pagamento.
2.Qual programa iniciou a solicitação?
R: O cliente iniciou a solicitação, enviando as horas e o valor por hora para o servidor.
3.O que aconteceria com o cliente se o servidor estivesse desligado?
R: O cliente não conseguiria se conectar ao servidor e apresentaria um erro na execução.
