# 🛒 Lista de Compras Inteligente

> 🚧 **Status:** Em desenvolvimento (Work in Progress). 
> O escopo deste projeto está em evolução. O foco atual é implementar e testar lógicas de análise de recorrência de compras utilizando SQL e Python.

## 🎯 O Projeto

Este é um Data App construído para facilitar o planejamento de compras. Ele analisa um histórico de idas ao supermercado para calcular a frequência com que cada item é comprado. A partir disso, o aplicativo cruza a data da última compra com os dias que você pretende ficar sem ir ao mercado para sugerir automaticamente o que precisa ser reposto.

**O que já está implementado:**
* Importação de histórico de compras via arquivo `.csv`.
* Armazenamento e persistência de dados em um banco de dados local (`SQLite`).
* Interface web interativa para definir a projeção de dias e visualizar a lista sugerida.

## 🚀 Tecnologias Utilizadas

* **Python**
* **Streamlit** (Interface Web)
* **Pandas** (Manipulação e Análise de Dados)
* **SQLite / SQLAlchemy** (Banco de Dados)

## 📁 Estrutura do Projeto

```text
├── data/
│   ├── init_data.csv         # Dados de exemplo para teste
│   └── database.db           # Banco de dados local (ignorado no versionamento)
├── sql/
│   └── query_inteligente.sql # Consulta SQL de recorrência
├── .gitignore
├── main.py                   # Ponto de entrada do aplicativo
└── requirements.txt          # Lista de dependências