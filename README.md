#🚀 Data Lake na AWS com Pipeline de Dados

Projeto prático que implementa um Data Lake escalável na AWS, com pipeline completa de dados: ingestão, ETL, processamento distribuído e organização em camadas (Bronze, Silver, Gold).

⚙️ Tecnologias
AWS S3 – Armazenamento de dados (Parquet)

AWS Glue – ETL, catálogo e qualidade de dados

AWS EMR + Apache Spark – Processamento distribuído

Python (boto3, urllib, BytesIO) – Ingestão e automação

IaC – Automação da infraestrutura

🧱 Etapas
Ingestão com Python e salvamento em Parquet no S3

ETL com Glue e estruturação da camada Silver

Processamento com EMR + Spark para camada Gold

Infraestrutura como Código para provisionamento automático
