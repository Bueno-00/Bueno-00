[Português](https://github.com/Bueno-00) · **English**

# Rafael Paganini Bueno

Automation and AI engineer. I build LLM agents, data pipelines and automations that remove manual work from businesses. Mid-level Automation Engineer at Ventura Group (an accounting group) and founder of Zemploo.

Personal page, with results, screenshots and resume: **https://zemploo.com.br/rafael-bueno** (open `#en` for English)

### AI projects (Nov 2026)

All with a README in Portuguese and English, a measured number and a live demo.

- **[Raio-X Fiscal](https://github.com/Bueno-00/raio-x-fiscal)** · [live app](https://raiox.zemploo.com.br): checks Brazilian e-invoices (XML) before they are imported into the accounting system, with a traffic light per item, the reason in plain language and a fix in the ERP's format. **78.7% NCM accuracy** in the test month, on 3.1 million public NF-e items; 184 of 186 planted errors flagged in the example invoices. Model and dataset on [Hugging Face](https://huggingface.co/RafaelBueno00/raio-x-fiscal-ncm-baseline), dataset and notebook on [Kaggle](https://www.kaggle.com/datasets/rafabueno/nfe-ncm-brasil-raio-x-fiscal).
- **[Pergunte ao Simples](https://github.com/Bueno-00/pergunte-ao-simples)** · [live, inside Raio-X](https://raiox.zemploo.com.br): a chat that answers about the Simples Nacional tax regime, MEI, NCM, NF-e and the tax reform citing the official source, with measured evaluation, attack defense and a spend cap. **97% on a 75-question answer key and about 82% on 68 new questions** (human review); 66 of 66 attacks blocked, 0 leaks.
- **[Catálogo de mercado](https://github.com/Bueno-00/catalogo-de-mercado)** · [demo](https://bueno-00.github.io/catalogo-de-mercado/): grocery product category from the name alone, comparing zero-shot LLM, TF-IDF and LoRA on the same test (Open Food Facts, Brazil). **81.5% with the classic model and the LLM combined** on unseen brands; 79.1% with the classic model alone, running in the browser. Data on [Kaggle](https://www.kaggle.com/datasets/rafabueno/catalogo-mercado-br).
- **[Próxima compra](https://github.com/Bueno-00/proxima-compra)** · [demo](https://bueno-00.github.io/proxima-compra/): recommends the next 10 products from what a person viewed, bought and searched for, 7 models on the same test (Diginetica). **84% of visits with at least 1 hit**; search signals add +20.7 points on products the person had not seen yet.

### Kaggle and Hugging Face

- **Hugging Face [RafaelBueno00](https://huggingface.co/RafaelBueno00):** model [raio-x-fiscal-ncm-baseline](https://huggingface.co/RafaelBueno00/raio-x-fiscal-ncm-baseline) (TF-IDF + hierarchical SVM, the model behind the app; model card in Portuguese and English) and dataset [nfe-ncm-brasil](https://huggingface.co/datasets/RafaelBueno00/nfe-ncm-brasil) (3.09 million public NF-e line items, anonymised, with a temporal split).
- **Kaggle [rafabueno](https://www.kaggle.com/rafabueno):** dataset [nfe-ncm-brasil-raio-x-fiscal](https://www.kaggle.com/datasets/rafabueno/nfe-ncm-brasil-raio-x-fiscal) and the notebook [raio-x-fiscal-ncm-baseline](https://www.kaggle.com/code/rafabueno/raio-x-fiscal-ncm-baseline), which reproduces the baseline; datasets [catalogo-mercado-br](https://www.kaggle.com/datasets/rafabueno/catalogo-mercado-br) (Open Food Facts, 41 categories, split by brand) and [catalogo-mercado-lora-v1-adapter](https://www.kaggle.com/datasets/rafabueno/catalogo-mercado-lora-v1-adapter) (the LoRA adapter from the grocery catalog project). The GPU notebooks (BERTimbau for Raio-X and LoRA for the catalog) live on the same profile.

### At the firm (Ventura Group)

Python and RPA automations for the Simples tax cycle, federal tax filings and the client portal: **about 331 hours a month of manual work automated from December on (about 284 hours today), close to 2 full-time people**. Volumes measured, minutes declared by the team. Details on the personal page.

AI formatter with a number check, measured before real use: on 42 synthetic documents, 2.53% of the numbers go missing with no check; with the improved check, 100% kept and 0 made up, for US$ 0.0053 more per document.

### Data engineering base (2025)

- [Databricks-Project](https://github.com/Bueno-00/Databricks-Project): financial and Bitcoin data pipeline on Databricks, Lakehouse architecture (bronze, silver, gold) with Lakeflow Declarative Pipelines.
- [Projeto-BikeStore---Arquitetura-Medallion](https://github.com/Bueno-00/Projeto-BikeStore---Arquitetura-Medallion): bronze, silver and gold layers on Databricks with Spark and SQL.
- [airflow-e-docker](https://github.com/Bueno-00/airflow-e-docker): pipeline orchestration environment with Apache Airflow on Docker Compose.
- [data-flow-orchestration](https://github.com/Bueno-00/data-flow-orchestration): ETL with Python, SQLite, Azure Blob Storage and Power BI.
- [portfolio-data-pipeline](https://github.com/Bueno-00/portfolio-data-pipeline): sales enrichment with PySpark on Databricks and ADLS Gen2, orchestrated with Azure Data Factory.

Full list: [projects-en](https://github.com/Bueno-00/projects-en)

### Stack
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![Claude API](https://img.shields.io/badge/Claude_API-191919?logo=anthropic&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?logo=huggingface&logoColor=black) ![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?logo=kaggle&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?logo=duckdb&logoColor=black) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)

Microsoft certifications: AZ-900 and DP-900. BSc in Software Engineering (UNOPAR, expected December 2028).

### Contact
[LinkedIn](https://www.linkedin.com/in/rafael-paganini-bueno) · rafapbueno29@gmail.com · [zemploo.com.br/rafael-bueno](https://zemploo.com.br/rafael-bueno) · [Kaggle](https://www.kaggle.com/rafabueno) · [Hugging Face](https://huggingface.co/RafaelBueno00)
