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
screenshots/
│
├── 01-customers.png
├── 02-orders.png
├── 03-products.png
├── 04-bronze-databricks.png
├── 05-order-items.png
├── 06-categoria.png
├── 07-produtos-mais-vendidos.png
├── 08-top-clientes.png
├── 09-vendas-por-estado.png
├── 10-resultado-final.png
└── 11-dashboard-final.png

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


## 1. Customers

<img width="1906" height="962" alt="costumers" src="https://github.com/user-attachments/assets/455a8fb8-d331-45cb-9739-7467fbec524f" />


**Descrição:**
Visualização dos dados de clientes extraídos do Supabase, representando a origem transacional do projeto.

---

## 2. Orders

<img width="1911" height="896" alt="ordens" src="https://github.com/user-attachments/assets/2dcf6911-28bf-423d-923f-2a8a6d88e5fb" />


**Descrição:**
Dados referentes aos pedidos realizados pelos clientes no ambiente de e-commerce.

---

## 3. Products

<img width="1900" height="879" alt="produtos" src="https://github.com/user-attachments/assets/f10ebcb0-f9a6-4bf4-9545-3ce331f9eedd" />


**Descrição:**
Catálogo de produtos utilizado para composição das análises de vendas.

---

## 4. Bronze Databricks

<img width="1916" height="967" alt="bronze databricks" src="https://github.com/user-attachments/assets/039a2bae-846b-49a4-abed-1f31d37d7aca" />


**Descrição:**
Evidência da ingestão dos dados no Databricks utilizando a camada Bronze da arquitetura Medallion.

---

## 5. Itens (Order Items)

<img width="1911" height="896" alt="ordens" src="https://github.com/user-attachments/assets/112a0037-aca1-4bf3-9749-a3a14301b5e2" />


**Descrição:**
Detalhamento dos itens presentes em cada pedido, permitindo a associação entre pedidos e produtos.

---

## 6. Categoria

<img width="1555" height="750" alt="categoria" src="https://github.com/user-attachments/assets/0e952898-15cd-4a15-a331-44aa34191e49" />


**Descrição:**
Indicador analítico demonstrando a distribuição das receitas por categoria de produto.

---

## 7. Produtos Mais Vendidos

<img width="1296" height="853" alt="produtos mais vendidos" src="https://github.com/user-attachments/assets/276d034f-83b7-4464-aac5-2ecf3d004128" />


**Descrição:**
Ranking dos produtos com maior volume de vendas dentro do período analisado.

---

## 8. Top Clientes

<img width="1376" height="781" alt="top clientes" src="https://github.com/user-attachments/assets/dee636cf-6dcb-4812-96a6-a824cb8045b0" />


**Descrição:**
Clientes que geraram maior receita para o negócio, evidenciando oportunidades para ações estratégicas.

---

## 9. Vendas por Estado

<img width="1400" height="724" alt="vendas por estado" src="https://github.com/user-attachments/assets/052a05f8-e2b4-4cf5-bd90-be62715fbd40" />


**Descrição:**
Análise geográfica das vendas realizadas, permitindo identificar os estados com melhor desempenho.

---

## 10. Resultado Final (KPI)

<img width="1456" height="724" alt="resultado final numero" src="https://github.com/user-attachments/assets/c3c7ec50-8eb9-4a9e-b579-28b35dbd802b" />


**Descrição:**
Indicador consolidado apresentando a receita total obtida no cenário analisado.

---
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

