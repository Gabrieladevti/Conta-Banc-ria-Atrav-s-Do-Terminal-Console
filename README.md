# Conta Bancária Através do Terminal Console

Este projeto é uma implementação simples de um sistema bancário, desenvolvido em **Java**, para gerenciar contas bancárias através do terminal. O objetivo é criar uma simulação de operações bancárias como depósito, saque, transferência e verificação de saldo utilizando um modelo de classes em Java.

## Funcionalidades

- **Criar Conta Bancária**: Permite criar uma nova conta bancária com saldo inicial e titular.
- **Depósito**: Realizar depósitos em uma conta bancária.
- **Saque**: Realizar saques, verificando se o saldo é suficiente.
- **Transferência**: Transferir dinheiro entre contas bancárias.
- **Exibição de Saldo**: Consultar o saldo atual da conta bancária.

## Tecnologias Utilizadas

- **Java**: A linguagem utilizada para o desenvolvimento do projeto.
- **Scanner**: Para receber entradas do usuário através do terminal.
- **Console**: Interface de entrada/saída que permite a interação com o usuário pelo terminal.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

- **ContaBancaria.java**: Classe principal que define a estrutura de uma conta bancária com atributos como titular e saldo.
- **Banco.java**: Classe responsável pelas operações bancárias, como realizar depósitos, saques e transferências.
- **Main.java**: Classe que contém o método `main`, que executa o menu de operações e interage com o usuário no terminal.

