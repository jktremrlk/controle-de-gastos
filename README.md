# Controle Financeiro Pessoal em Python

Este projeto é um sistema simples de controle financeiro pessoal, desenvolvido em Python, que permite ao usuário:

- Calcular o saldo disponível após considerar salário, economia e gastos fixos;
- Adicionar, visualizar e apagar despesas categorizadas;
- Criar um arquivo JSON para armazenar dados de gastos em uma pasta específica;
- Visualizar os dados salvos no arquivo JSON diretamente no terminal.

---

## 📂 Estrutura do projeto

controle-financeiro/
│
├── main.py # Arquivo principal com interface de menu e classe Planejar
├── calcular.py # Classe Calculando com lógica para despesas e cálculos
└── gastos/ # Pasta criada automaticamente para armazenar dados.json
