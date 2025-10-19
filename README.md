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

- Criação de tabelas: CREATE TABLE para estruturar bases de dados.
- Inserção de registros: INSERT INTO para popular tabelas com dados de exemplo.
- Consultas de dados: SELECT para extrair informações.
- Filtragem: WHERE para selecionar dados específicos.
- Ordenação: ORDER BY para organizar os resultados.
- Agrupamento de dados: GROUP BY com funções agregadas (COUNT, SUM, AVG) para análises resumidas.
- Execução de SQL no notebook: %%sql para rodar queries diretamente em células Jupyter.
- Subconsultas: utilização de queries dentro de outras queries para resultados mais complexos.
- Junções: JOIN para combinar dados de múltiplas tabelas.
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
