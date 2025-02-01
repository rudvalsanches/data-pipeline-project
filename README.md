# Data Pipeline Project 🚀

Este projeto demonstra uma arquitetura completa de Engenharia de Dados, incluindo ingestão, processamento, armazenamento e visualização.

## 🔹 Tecnologias Utilizadas:
- 🐳 Docker + WSL2
- 🏗️ Apache Airflow (Orquestração)
- 🔥 Apache Spark (Processamento)
- 🗄️ PostgreSQL (Banco de Dados)
- ☁️ MinIO (Simulação do AWS S3 - Data Lake)
- 📊 Grafana + Prometheus (Monitoramento)
- 📈 Metabase (Visualização de Dados)

## 📂 Estrutura do Projeto:# data-pipeline-project

📁 data-pipeline-project 
│── 📁 airflow/ # DAGs do Airflow 
│── 📁 ingestion/ # Scripts de ingestão (Python) 
│── 📁 processing/ # Scripts de processamento (Spark/Pandas) 
│── 📁 storage/ # Configuração do PostgreSQL e MinIO 
│── 📁 monitoring/ # Prometheus e Grafana 
│── 📁 visualization/ # Configuração do Metabase 
│── 📁 docker/ # Arquivos Docker 
│── 📄 README.md # Documentação 
│── 📄 docker-compose.yml # Arquitetura Docker 
│── 📄 requirements.txt # Dependências do Python