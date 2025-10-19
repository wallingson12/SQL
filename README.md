# SQL QUERYS 🧠

Este notebook demonstra o uso prático de **consultas SQL** executadas diretamente em um ambiente **Jupyter Notebook**, utilizando o **DuckDB** como mecanismo de banco de dados leve e rápido.

## 💾 Objetivo

O projeto tem como finalidade apresentar, de forma interativa, exemplos de criação, inserção e consulta de dados em SQL, permitindo testar e visualizar resultados instantaneamente dentro do próprio notebook.

## ⚙️ Tecnologias Utilizadas

- **Jupyter Notebook**
- **DuckDB**
- **JupySQL** (`ipython-sql` aprimorado)
- **Python 3**

## 🧰 Funcionalidades Demonstradas

- Criação de tabelas (`CREATE TABLE`)
- Inserção de registros (`INSERT INTO`)
- Consulta de dados (`SELECT`)
- Execução de queries SQL diretamente em células do notebook com `%%sql`

## 🚀 Como Executar

1. Instale as dependências necessárias:
2. Execute o notebook no Jupyter:
   jupyter notebook "SQL QUERYS.ipynb"
3. As primeiras células já configuram o ambiente:
   !pip install jupysql duckdb-engine
    %load_ext sql
    %sql duckdb://

📈 Resultados

O notebook exibe, diretamente no output de cada célula, os resultados das consultas SQL formatados em tabela, 
facilitando o aprendizado e a experimentação.

   ```bash
   pip install jupysql duckdb-engine
