# Sistema Bancário

Este é um sistema bancário simples implementado em Python. Ele permite que o usuário faça depósitos, saques e visualize o extrato de sua conta. Além disso, o sistema tem um limite diário de saques.

## Funcionalidades

O sistema oferece as seguintes funcionalidades:

- **Depósito:** Permite que o usuário deposite uma quantia na conta.
- **Saque:** Permite que o usuário retire dinheiro da conta, respeitando um limite de valor por saque e um limite de três saques diários.
- **Extrato:** Mostra todas as transações realizadas (depósitos e saques) e o saldo atual da conta.
- **Sair:** Finaliza o programa.

## Regras do Sistema

1. **Depósitos:**
   - O valor deve ser positivo.
   - O saldo é atualizado automaticamente após o depósito.

2. **Saques:**
   - O número máximo de saques por dia é de 3.
   - O valor do saque não pode exceder o saldo disponível.
   - O valor do saque não pode exceder o limite diário de R$ 500,00.

3. **Extrato:**
   - Exibe todas as transações realizadas.
   - Mostra o saldo atual da conta.

## Como Usar

1. Clone o repositório ou copie o código para seu ambiente local.
2. Execute o arquivo Python.
3. Utilize o menu interativo para realizar operações bancárias:

   - `[d] Depositar`: Insira o valor que deseja depositar.
   - `[s] Sacar`: Insira o valor que deseja sacar, respeitando os limites.
   - `[e] Extrato`: Visualize o extrato e saldo da conta.
   - `[q] Sair`: Finalize o programa.
