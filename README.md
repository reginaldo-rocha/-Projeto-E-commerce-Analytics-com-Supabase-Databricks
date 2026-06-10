# 🚀 Projeto  — E-commerce Analytics com Supabase + Databricks

## 📌 Objetivo
Desenvolver uma solução analítica ponta a ponta utilizando a **Arquitetura Medallion** para consolidar e analisar dados transacionais de um e-commerce, desde a origem operacional até a geração de KPIs de negócio e dashboards executivos.

Supabase (Postgres) ➡️ Exportação CSV ➡️ Databricks Volumes ➡️ Camada Bronze ➡️ Camada Silver ➡️ Camada Gold ➡️ Dashboard

## 🏗️ Arquitetura e Fluxo de Dados

<img width="1193" height="880" alt="Gemini_Generated_Image_jbhl1sjbhl1sjbhl" src="https://github.com/user-attachments/assets/2385ed4b-0006-407a-a245-4058220acb78" />


# 🛠️ Stack

* Supabase (PostgreSQL)
* Databricks SQL
* Databricks Volumes
* SQL
* Arquitetura Medallion
* Dashboard Databricks
* GitHub

---

# 📂 Estrutura

```text
projeto9-ecommerce-databricks/
│
├── sql/
│   ├── bronze.sql
│   ├── silver.sql
│   └── gold.sql
│
├── screenshots/
│   ├── 01-customers.png
│   ├── 02-orders.png
│   ├── 03-products.png
│   ├── 04-bronze-databricks.png
│   ├── 05-order-items.png
│   ├── 06-categoria.png
│   ├── 07-produtos-mais-vendidos.png
│   ├── 08-top-clientes.png
│   ├── 09-vendas-por-estado.png
│   ├── 10-resultado-final.png
│   └── 11-dashboard-final.png
│
├── README.md
└── .gitignore
```

---

# ⚙️ Pipeline

1. Criação das tabelas transacionais no Supabase
2. Inserção dos dados do e-commerce
3. Exportação das tabelas para arquivos CSV
4. Upload dos arquivos para Databricks Volumes
5. Construção da camada Bronze
6. Tratamento e integração dos dados na camada Silver
7. Desenvolvimento dos KPIs na camada Gold
8. Construção do Dashboard analítico

---

# 📸 Evidências do Projeto

## 1. Customers

**Arquivo:** `01-customers.png`

<img width="1906" height="962" alt="costumers" src="https://github.com/user-attachments/assets/fc374b61-45d6-4d89-bd6c-001dcb6077e6" />


Visualização dos dados de clientes extraídos do Supabase.

---

## 2. Orders

**Arquivo:** `02-orders.png`

<img width="1911" height="896" alt="ordens" src="https://github.com/user-attachments/assets/dfa92882-15fd-4fdb-b1a3-06b11d61b2d9" />


Dados referentes aos pedidos realizados pelos clientes.

---

## 3. Products

**Arquivo:** `03-products.png`

<img width="1900" height="879" alt="produtos" src="https://github.com/user-attachments/assets/21d63d85-5fcd-43a5-bfbe-768936cf0eba" />


Catálogo de produtos utilizado nas análises.

---

## 4. Bronze Databricks

**Arquivo:** `04-bronze-databricks.png`

<img width="1916" height="967" alt="bronze databricks" src="https://github.com/user-attachments/assets/48794db6-0966-4016-8e5a-503aee9fbc6a" />


Evidência da ingestão dos dados no Databricks utilizando a camada Bronze.

---

## 5. Order Items

**Arquivo:** `05-order-items.png`

<img width="1902" height="865" alt="itens" src="https://github.com/user-attachments/assets/fad8aeb2-9b99-431b-bcda-f883139f6283" />


Detalhamento dos itens presentes em cada pedido.

---

## 6. Receita por Categoria

**Arquivo:** `06-categoria.png`

<img width="1555" height="750" alt="categoria" src="https://github.com/user-attachments/assets/e066cfa1-193a-4336-a3e5-ef567256ce49" />


Análise da distribuição da receita por categoria de produto.

---

## 7. Produtos Mais Vendidos

**Arquivo:** `07-produtos-mais-vendidos.png`

<img width="1296" height="853" alt="produtos mais vendidos" src="https://github.com/user-attachments/assets/72e01f51-5926-4e75-bf9f-c891d9cb4356" />


Ranking dos produtos com maior volume de vendas.

---

## 8. Top Clientes

**Arquivo:** `08-top-clientes.png`

<img width="1376" height="781" alt="top clientes" src="https://github.com/user-attachments/assets/765665a9-c6ea-445d-9a42-e5450686446d" />


Clientes responsáveis pela maior geração de receita.

---

## 9. Vendas por Estado

**Arquivo:** `09-vendas-por-estado.png`

<img width="1400" height="724" alt="vendas por estado" src="https://github.com/user-attachments/assets/ef6bca7a-b6e5-4ceb-9491-bc4448be7126" />


Distribuição geográfica das vendas realizadas.

---

## 10. Receita Total

**Arquivo:** `10-resultado-final.png`

<img width="1456" height="724" alt="resultado final numero" src="https://github.com/user-attachments/assets/9450870e-a7c9-4496-9bd0-44d6d301130d" />


Indicador consolidado da receita total do e-commerce.

---

# 📊 KPIs Desenvolvidos

* Receita Total
* Receita por Categoria
* Produtos Mais Vendidos
* Top Clientes
* Vendas por Estado

---

# 📚 Série de Projetos em Data Engineering

✅ Projeto 1 — API + SQL

✅ Projeto 2 — Data Warehouse

✅ Projeto 3 — Pipeline contínuo + histórico

✅ Projeto 4 — Cloud + Orquestração

✅ Projeto 5 — AWS EC2 + PostgreSQL + Cloud Pipeline

✅ Projeto 6 — Docker + PostgreSQL + ETL Python

✅ Projeto 7 — Airflow + PostgreSQL + Docker

✅ Projeto 8 — PySpark + Data Lake + Airflow + MinIO

✅ 🚀 Projeto 9 — E-commerce Analytics com Supabase + Databricks

---

# 🎯 Objetivos Trabalhados

* Modelagem de dados transacionais
* Ingestão de dados no Databricks
* Implementação da arquitetura Medallion
* Construção das camadas Bronze, Silver e Gold
* Desenvolvimento de consultas analíticas com SQL
* Criação de KPIs de negócio
* Construção de dashboards analíticos
* Organização de projetos para portfólio
* Aplicação de boas práticas em Engenharia de Dados
* Integração entre banco operacional e ambiente analítico

---

# 👨‍💻 Autor

**Reginaldo Rocha**

💼 LinkedIn: https://www.linkedin.com/in/reginaldorochacloud/





