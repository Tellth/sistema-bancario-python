# Sistema Bancário v3.0 em Python

Sistema bancário simples em linha de comando (CLI) desenvolvido para praticar **Programação Orientada a Objetos**, validações, controle de limites e boa organização de código.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20desenvolvimento-yellow)

## Funcionalidades Principais (v3.0)

- Cadastro de usuários (com CPF único)
- Criação de múltiplas contas por usuário
- Depósitos ilimitados
- Saques com limite diário (R$ 500 por saque / máximo 3 saques por dia)
- Limite geral de 10 transações por dia
- Extrato completo com data/hora
- Reset automático de limites ao mudar o dia
- Menu interativo intuitivo

## Tecnologias e Conceitos Aplicados

- Python 3.x
- Programação Orientada a Objetos (classes, herança, encapsulamento)
- Tratamento de exceções e validações robustas
- Uso de `datetime` para controle temporal
- Listas para histórico de transações
- Funções auxiliares bem organizadas

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Tellth/sistema-bancario-python.git
   cd sistema-bancario-python
2. Execute o programa:
   ```bash
   python sistema-bancario-v3.0.py
