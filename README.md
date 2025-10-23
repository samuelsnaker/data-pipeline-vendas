# 🧾 Data Pipeline de Vendas

**Data Pipeline de Vendas** é um projeto prático e educativo desenvolvido para aprender e aplicar os principais conceitos do ecossistema de dados moderno.  

O objetivo é construir, passo a passo, um pipeline completo que:

- Extrai dados de vendas de um arquivo CSV  
- Transforma e limpa com **Pandas** e **Spark**  
- Carrega em um banco **SQLite**  
- Executa análises SQL com **Window Functions**  
- Orquestra tudo com **Apache Airflow**

Além da parte técnica, o projeto segue princípios de **Clean Code** e **SOLID**, incentivando boas práticas de programação, modularização e versionamento com **GitHub**.

---

## 💡 Objetivos do Projeto

- Aprender na prática manipulação de dados em **Python** e **SQL**  
- Entender o funcionamento de **pipelines ETL** modernos  
- Experimentar o uso do **Airflow** e do **Spark** em um projeto simples  
- Aplicar boas práticas de **engenharia de dados** e **código limpo**

---

## 🧠 Tecnologias Utilizadas

- **Python 3**
- **Pandas**
- **PySpark**
- **SQLite / SQL**
- **Apache Airflow**
- **GitHub Actions** (para CI/CD)
- **Pytest, Black e Flake8** (para testes e qualidade de código)

---

## 🏗️ Estrutura do Projeto

data-pipeline-vendas/
│
├── dags/ # DAGs do Airflow
│ └── vendas_dag.py
│
├── scripts/ # Scripts de extração, transformação e carga
│ ├── extract_data.py
│ ├── transform_pandas.py
│ ├── transform_spark.py
│ ├── load_sqlite.py
│ └── analyze_sql.py
│
├── data/ # Dados brutos e processados
│ ├── raw/
│ │ └── vendas.csv
│ └── processed/
│ └── vendas_limpa.csv
│
├── tests/ # Testes unitários
│ └── test_transform.py
│
├── requirements.txt
├── README.md
└── .github/workflows/ci.yml # CI opcional (lint + teste)


---

## 🚀 Próximos Passos

- [ ] Criar DAG no Airflow com as etapas Extract → Transform → Load → Analyze  
- [ ] Adicionar testes unitários e checagem de estilo de código  
- [ ] Integrar com GitHub Actions para automação  
- [ ] Criar dashboard simples com Streamlit (opcional)

---

## 🧩 Autor

Desenvolvido por **Samuel Alves** 🧠  
📍 Projeto educacional e open source para aprendizado de engenharia de dados.  
