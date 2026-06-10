# 🚀 Projeto 9 — E-commerce Analytics com Supabase + Databricks

## 📌 Objetivo

Desenvolver uma solução analítica utilizando arquitetura Medallion para consolidar e analisar dados de um ambiente de e-commerce, desde a origem transacional até a geração de KPIs e dashboards.

---

# 🏗️ Arquitetura

Supabase → CSV → Databricks Volumes → Bronze → Silver → Gold → Dashboard

<img width="1193" height="880" alt="Gemini_Generated_Image_jbhl1sjbhl1sjbhl" src="https://github.com/user-attachments/assets/bcbd679f-40ad-442c-bf9e-4436b7b4e705" />


---

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

```
projeto9-ecommerce-databricks/
│
├── sql/
│   ├── bronze.sql
│   ├── silver.sql
│   └── gold.sql
│
├── screenshots/
│   ├── 01-arquitetura.png
│   ├── 02-supabase.png
│   ├── 03-bronze.png
│   ├── 04-silver.png
│   ├── 05-gold.png
│   └── 06-dashboard.png
│
├── docs/
│   └── arquitetura.drawio
│
├── README.md
└── .gitignore
```

---

# ⚙️ Pipeline

1. Criação das tabelas transacionais no Supabase
2. Inserção dos dados do e-commerce
3. Exportação das tabelas para CSV
4. Upload dos arquivos para Volumes no Databricks
5. Construção da camada Bronze
6. Tratamento e integração dos dados na camada Silver
7. Criação dos KPIs na camada Gold
8. Desenvolvimento do Dashboard analítico

---

# 📸 Sequência dos Prints - Projeto 9

## 1. Customers

**Arquivo:** `01-customers.png`

**Descrição:**
Visualização dos dados de clientes extraídos do Supabase, representando a origem transacional do projeto.

---

## 2. Orders

**Arquivo:** `02-orders.png`

**Descrição:**
Dados referentes aos pedidos realizados pelos clientes no ambiente de e-commerce.

---

## 3. Products

**Arquivo:** `03-products.png`

**Descrição:**
Catálogo de produtos utilizado para composição das análises de vendas.

---

## 4. Bronze Databricks

**Arquivo:** `04-bronze-databricks.png`

**Descrição:**
Evidência da ingestão dos dados no Databricks utilizando a camada Bronze da arquitetura Medallion.

---

## 5. Itens (Order Items)

**Arquivo:** `05-order-items.png`

**Descrição:**
Detalhamento dos itens presentes em cada pedido, permitindo a associação entre pedidos e produtos.

---

## 6. Categoria

**Arquivo:** `06-categoria.png`

**Descrição:**
Indicador analítico demonstrando a distribuição das receitas por categoria de produto.

---

## 7. Produtos Mais Vendidos

**Arquivo:** `07-produtos-mais-vendidos.png`

**Descrição:**
Ranking dos produtos com maior volume de vendas dentro do período analisado.

---

## 8. Top Clientes

**Arquivo:** `08-top-clientes.png`

**Descrição:**
Clientes que geraram maior receita para o negócio, evidenciando oportunidades para ações estratégicas.

---

## 9. Vendas por Estado

**Arquivo:** `09-vendas-por-estado.png`

**Descrição:**
Análise geográfica das vendas realizadas, permitindo identificar os estados com melhor desempenho.

---

## 10. Resultado Final (KPI)

**Arquivo:** `10-resultado-final.png`

**Descrição:**
Indicador consolidado apresentando a receita total obtida no cenário analisado.

---

## 11. Dashboard Final

**Arquivo:** `11-dashboard-final.png`

**Descrição:**
Dashboard analítico contendo os principais KPIs do projeto, proporcionando uma visão executiva do desempenho do e-commerce.


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
* Organização de projeto profissional para portfólio
* Aplicação de boas práticas em Engenharia de Dados
* Integração entre banco operacional e ambiente analítico


# 👨‍💻 Autor

Reginaldo Rocha

💼 LinkedIn:https://www.linkedin.com/in/reginaldorochacloud/

