# Sistema Bancário em Python

Este é um projeto de sistema bancário simples desenvolvido em Python, que oferece funcionalidades básicas de uma conta bancária.

## Funcionalidades

- **Depósito**: Permite realizar depósitos de valores positivos na conta.
- **Saque**: Permite realizar saques com as seguintes regras:
  - Limite de 3 saques diários
  - Valor máximo de R$ 500,00 por saque
  - Necessário ter saldo suficiente
- **Extrato**: Exibe todas as movimentações realizadas na conta e o saldo atual.

## Como usar

1. Execute o arquivo `sistema_bancario.py`
2. Utilize o menu interativo para selecionar as operações:
   - [d] para Depositar
   - [s] para Sacar
   - [e] para ver o Extrato
   - [q] para Sair

## Requisitos

- Python 3.x