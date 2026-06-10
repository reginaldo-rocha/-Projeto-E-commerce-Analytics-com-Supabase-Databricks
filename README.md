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

Visualização dos dados de clientes extraídos do Supabase.

---

## 2. Orders

**Arquivo:** `02-orders.png`

Dados referentes aos pedidos realizados pelos clientes.

---

## 3. Products

**Arquivo:** `03-products.png`

Catálogo de produtos utilizado nas análises.

---

## 4. Bronze Databricks

**Arquivo:** `04-bronze-databricks.png`

Evidência da ingestão dos dados no Databricks utilizando a camada Bronze.

---

## 5. Order Items

**Arquivo:** `05-order-items.png`

Detalhamento dos itens presentes em cada pedido.

---

## 6. Receita por Categoria

**Arquivo:** `06-categoria.png`

Análise da distribuição da receita por categoria de produto.

---

## 7. Produtos Mais Vendidos

**Arquivo:** `07-produtos-mais-vendidos.png`

Ranking dos produtos com maior volume de vendas.

---

## 8. Top Clientes

**Arquivo:** `08-top-clientes.png`

Clientes responsáveis pela maior geração de receita.

---

## 9. Vendas por Estado

**Arquivo:** `09-vendas-por-estado.png`

Distribuição geográfica das vendas realizadas.

---

## 10. Receita Total

**Arquivo:** `10-resultado-final.png`

Indicador consolidado da receita total do e-commerce.

---

## 11. Dashboard Final

**Arquivo:** `11-dashboard-final.png`

Dashboard contendo os principais indicadores desenvolvidos no projeto.

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





