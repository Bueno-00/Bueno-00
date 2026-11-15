**Português** · [English](https://github.com/Bueno-00/Bueno-00/blob/main/README.en.md)

# Rafael Paganini Bueno

Engenheiro de automação e IA. Construo agentes com LLM, pipelines de dados e automações que tiram trabalho manual de empresas. Engenheiro de Automação Pleno no Ventura Group (grupo contábil) e fundador da Zemploo.

Página pessoal, com resultados, prints e currículo: **https://zemploo.com.br/rafael-bueno**

### Projetos de IA (nov/2026)

Todos com README em português e inglês, número medido e demonstração no ar.

- **[Raio-X Fiscal](https://github.com/Bueno-00/raio-x-fiscal)** · [app no ar](https://raiox.zemploo.com.br): confere notas fiscais (XML) antes de importar no sistema contábil, com semáforo por item, motivo em português e correção no formato do sistema. **78,7% de acerto do NCM** no mês de teste, sobre 3,1 milhões de itens de NF-e públicas; 184 de 186 erros plantados marcados nas notas de exemplo. Modelo e dataset no [Hugging Face](https://huggingface.co/RafaelBueno00/raio-x-fiscal-ncm-baseline), dataset e notebook no [Kaggle](https://www.kaggle.com/datasets/rafabueno/nfe-ncm-brasil-raio-x-fiscal).
- **[Pergunte ao Simples](https://github.com/Bueno-00/pergunte-ao-simples)** · [no ar, dentro do Raio-X](https://raiox.zemploo.com.br): chat que responde sobre Simples Nacional, MEI, NCM, NF-e e reforma tributária citando a fonte oficial, com avaliação medida, defesa contra ataque e teto de gasto. **97% no gabarito de 75 perguntas e cerca de 82% em 68 perguntas novas** (revisão humana); 66 de 66 ataques barrados, 0 vazamento.
- **[Catálogo de mercado](https://github.com/Bueno-00/catalogo-de-mercado)** · [demonstração](https://bueno-00.github.io/catalogo-de-mercado/): diz a categoria de um produto de mercado só pelo nome, comparando IA sem treino, TF-IDF e LoRA no mesmo teste (Open Food Facts, Brasil). **81,5% com o clássico e a IA juntos** em marcas nunca vistas; 79,1% só o clássico, rodando no navegador. Dados no [Kaggle](https://www.kaggle.com/datasets/rafabueno/catalogo-mercado-br).
- **[Próxima compra](https://github.com/Bueno-00/proxima-compra)** · [demonstração](https://bueno-00.github.io/proxima-compra/): recomenda os 10 próximos produtos a partir do que a pessoa viu, comprou e pesquisou, 7 modelos no mesmo teste (Diginetica). **84% das visitas com pelo menos 1 acerto**; a busca soma +20,7 pontos nos produtos que a pessoa ainda não tinha visto.

### Kaggle e Hugging Face

- **Hugging Face [RafaelBueno00](https://huggingface.co/RafaelBueno00):** modelo [raio-x-fiscal-ncm-baseline](https://huggingface.co/RafaelBueno00/raio-x-fiscal-ncm-baseline) (TF-IDF + SVM hierárquico, o modelo que roda no app; model card em português e inglês) e dataset [nfe-ncm-brasil](https://huggingface.co/datasets/RafaelBueno00/nfe-ncm-brasil) (3,09 milhões de itens de NF-e públicas, anonimizado, com divisão por mês).
- **Kaggle [rafabueno](https://www.kaggle.com/rafabueno):** dataset [nfe-ncm-brasil-raio-x-fiscal](https://www.kaggle.com/datasets/rafabueno/nfe-ncm-brasil-raio-x-fiscal) e o notebook [raio-x-fiscal-ncm-baseline](https://www.kaggle.com/code/rafabueno/raio-x-fiscal-ncm-baseline), que reproduz o baseline; datasets [catalogo-mercado-br](https://www.kaggle.com/datasets/rafabueno/catalogo-mercado-br) (Open Food Facts, 41 categorias, divisão por marca) e [catalogo-mercado-lora-v1-adapter](https://www.kaggle.com/datasets/rafabueno/catalogo-mercado-lora-v1-adapter) (o adapter LoRA do Catálogo de mercado). Os notebooks de GPU (BERTimbau do Raio-X e LoRA do Catálogo) ficam no mesmo perfil.

### No escritório (Ventura Group)

Automações em Python e RPA do ciclo fiscal do Simples, das obrigações na Receita e da publicação no portal do cliente: **cerca de 331 h por mês de trabalho à mão automatizadas a partir de dezembro (cerca de 284 h hoje), perto de 2 pessoas em tempo integral**. Volumes medidos, minutos declarados pela equipe. Detalhe na página pessoal.

Formatador com IA com trava numérica, medido antes de ir para uso real: em 42 documentos fictícios, sem trava 2,53% dos números somem; com a trava melhorada, 100% preservados e 0 inventado, por US$ 0,0053 a mais por documento.

### Base de engenharia de dados (2025)

- [Databricks-Project](https://github.com/Bueno-00/Databricks-Project): pipeline financeiro e de Bitcoin no Databricks, arquitetura Lakehouse (bronze, prata, ouro) com Lakeflow Declarative Pipelines.
- [Projeto-BikeStore---Arquitetura-Medallion](https://github.com/Bueno-00/Projeto-BikeStore---Arquitetura-Medallion): camadas bronze, prata e ouro no Databricks com Spark e SQL.
- [airflow-e-docker](https://github.com/Bueno-00/airflow-e-docker): ambiente de orquestração de pipelines com Apache Airflow em Docker Compose.
- [data-flow-orchestration](https://github.com/Bueno-00/data-flow-orchestration): ETL com Python, SQLite, Azure Blob Storage e Power BI.
- [portfolio-data-pipeline](https://github.com/Bueno-00/portfolio-data-pipeline): enriquecimento de vendas com PySpark no Databricks e ADLS Gen2, orquestrado no Azure Data Factory.

Lista completa: [projetos-pt](https://github.com/Bueno-00/projetos-pt)

### Stack
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![Claude API](https://img.shields.io/badge/Claude_API-191919?logo=anthropic&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?logo=huggingface&logoColor=black) ![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?logo=kaggle&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?logo=duckdb&logoColor=black) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)

Certificações Microsoft: AZ-900 e DP-900. Graduação em Engenharia de Software (UNOPAR, conclusão prevista em dezembro de 2028).

### Contato
[LinkedIn](https://www.linkedin.com/in/rafael-paganini-bueno) · rafapbueno29@gmail.com · [zemploo.com.br/rafael-bueno](https://zemploo.com.br/rafael-bueno) · [Kaggle](https://www.kaggle.com/rafabueno) · [Hugging Face](https://huggingface.co/RafaelBueno00)
