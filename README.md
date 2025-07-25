# Sistema Bancário em Python

Este é um sistema bancário simples, feito em Python, com as funcionalidades básicas de:

- Depósito
- Saque (com limite de valor e quantidade por dia)
- Extrato de movimentações
- Cadastro de usuários
- Criação e listagem de contas bancárias

Perfeito para treinar **lógica de programação**, **organização em funções**, **validações** e **interação com o usuário via terminal**.


## Como usar

bash
### Clone o repositório:
git clone https://github.com/Alyhrvds/Otimizando-o-Sistema-Bancario-com-Funcoes-Python.git

### Acesse a pasta do projeto:
cd Criando-um-Sistema-Bancario-com-Python

### Execute o programa:
python sistemaBancario.py


## Funcionalidades

### Depósito

* Aceita apenas valores positivos
* Atualiza o saldo
* Registra a transação no extrato

### Saque

* Limite diário de **3 saques**
* Limite por saque de **R\$ 500,00**
* Não permite sacar mais do que o saldo disponível
* Atualiza o saldo e registra no extrato

### Extrato

* Mostra o histórico completo de movimentações
* Exibe o saldo atual
* Informa se nenhuma operação foi realizada

### Cadastro de Usuários

* Registra nome, data de nascimento, CPF e endereço
* Verifica se o CPF já está cadastrado

### Conta Bancária

* Cria contas vinculadas a usuários existentes
* Exibe lista de contas cadastradas com nome e agência


## Tecnologias

* Python 3
* Terminal / Linha de comando

## Autor

Feito com amor por **Alice**.

## Inspiração

Este projeto foi baseado em um exercício proposto durante os estudos em Python na plataforma **DIO**.
A versão 2 aqui apresentada inclui:

* Estrutura em **funções reutilizáveis**
* Separação clara entre **usuários, contas e transações**
* Mensagens mais intuitivas
* Melhor organização e legibilidade do código

## Observações

Este projeto é ideal para iniciantes e pode ser expandido para:

* Login com autenticação
* Armazenamento em banco de dados
* Interface gráfica (Tkinter, PyQt, etc)
* API REST para acesso externo
* Testes automatizados

Sinta-se à vontade para contribuir ou personalizar o código! 😄

