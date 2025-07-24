# 🔄 Pipeline de Dados com Power BI e Azure

Este projeto é uma Prova de Conceito (PoC) para uma entrevista técnica. Ele demonstra a construção de um pipeline de dados completo, partindo de arquivos JSON até a visualização em dashboards Power BI, passando por tratamento com Python, ingestão via Azure Data Factory e persistência em Data Warehouse.

---

## 🧠 Objetivo

Transformar e estruturar dados de interações em redes sociais para análise de engajamento, usuários e padrões de comportamento.

---

## ⚙️ Tecnologias Utilizadas

- **Python** (ETL com Pandas)
- **Databricks** (execução dos notebooks)
- **Azure Data Factory** (orquestração)
- **SQL Data Warehouse**
- **Power BI** (visualização de dados)

---

## 📁 Estrutura do Projeto

├── etl_pipeline.ipynb
├── data/
│   ├── comments_data.xlsx
│   ├── posts_data.xlsx
│   ├── posts_options.xlsx
│   ├── translation.xlsx
│   ├── user.xlsx
│   └── votes.xlsx
├── json/
│   ├── posts_comments.xlsx
│   ├── posts_data.json
│   └── users_data.json
📄 etl_pipeline.ipynb

## 🔄 Etapas do Pipeline

1. **Carregamento** dos arquivos JSON e Excel.
2. **Transformação** dos dados em tabelas normalizadas.
3. **Envio para Data Warehouse**.
4. **Visualização** em Power BI com atualização a cada 2 horas.

---

## 📊 Link do Dashboard

[🔗 Acessar Power BI](https://app.powerbi.com/view?r=eyJrIjoiNDQ5MTdlMzAtMDhiMS00ZTUxLWE3N2UtNTU1ZjI5OTg1YTQ2IiwidCI6ImQ5ZDliZDhiLTNmMzQtNDQyMy05MmY5LWNmZTg1NDI1MTY1YSJ9)

---

## 📈 Métricas Principais

- Engajamento por Post
- Total de Usuários
- Usuários que são Patronos
- Interações por Post (comentários e votos)
- Pontuação de Envolvimento
- Quantidade de Posts por Dia

---

## 📌 Observações

Este projeto foi desenvolvido em um contexto técnico simulado, mas representa uma arquitetura realista para ingestão e análise de dados em escala.
