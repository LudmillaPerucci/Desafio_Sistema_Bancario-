# Desafio: Sistema Bancário em Python

## Objetivo

O objetivo deste desafio foi criar um sistema bancário simples utilizando Python. O sistema permite realizar operações básicas como depósitos, saques, e consultas de saldo, além de manter um histórico das transações realizadas.

## Funcionalidades Implementadas

### 1. **Menu de Opções**

O sistema apresenta um menu interativo com as seguintes opções:
- **[1] Depositar:** Permite que o usuário deposite uma quantia em sua conta.
- **[2] Sacar:** Permite que o usuário retire uma quantia de sua conta, com controle de saldo e limites.
- **[3] Extrato:** Exibe o extrato com o histórico de transações e o saldo atual.
- **[4] Sair:** Encerra a execução do programa.

### 2. **Depósitos**

- O usuário pode informar o valor que deseja depositar.
- O valor é adicionado ao saldo da conta.
- O depósito é registrado no extrato com a data e valor correspondente.
- É feita uma validação para garantir que o valor seja positivo.

### 3. **Saques**

- O usuário pode informar o valor que deseja sacar.
- O sistema realiza as seguintes validações:
  - **Saldo:** Verifica se há saldo suficiente na conta.
  - **Limite:** Verifica se o valor do saque não excede o limite diário.
  - **Número de Saques:** Limita o número máximo de saques permitidos.
- O saque é registrado no extrato e o saldo é atualizado.
- É feita uma validação para garantir que o valor seja positivo.

### 4. **Extrato**

- Exibe o histórico completo de depósitos e saques realizados.
- Mostra o saldo atual da conta.
- Informa se não foram realizadas movimentações.
