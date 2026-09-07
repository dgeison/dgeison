# Índice de repositórios

Catálogo de todos os repositórios, organizado por tipo. Serve como camada de
busca sobre o histórico técnico — tanto para quem visita o perfil quanto como
referência rápida em sessões futuras com LLM.

Última atualização: 2026-09-06.

## Como isso é organizado

- **Um repositório por projeto** (polyrepo), exceto exercícios pontuais de
  estudo, que ficam agrupados em `data-science-estudos` para não pulverizar
  o perfil em dezenas de repositórios de uma linha só.
- **Público por padrão**, exceto quando: o conteúdo inclui material de
  terceiros com direito autoral (apostilas, slides de curso), é produto/site
  de cliente, ou ainda não tem valor de portfólio pronto para mostrar.
- **Dados grandes nunca vão para o Git** — ficam de fora via `.gitignore` e o
  README de cada repo documenta a fonte pública para reproduzir.
- Antes de publicar algo novo, checar se já não existe (nome parecido, mesmo
  dataset) para não duplicar.

## Projetos flagship (produção / portfólio principal)

| Repo | Sobre |
|---|---|
| [saas-gabinete](https://github.com/dgeison/saas-gabinete) 🔒 | SaaS de Gabinete — Sistema Operacional de Mandato com IA segura (produto real, tangerina.cloud) |
| [fhir-datavault-postgres](https://github.com/dgeison/fhir-datavault-postgres) | FHIR → Data Vault 2.0 em PostgreSQL: hash keys, hashdiff, carga idempotente e versionada |
| [lakehouse-pyspark-scd2](https://github.com/dgeison/lakehouse-pyspark-scd2) | Pipeline Bronze/Silver/Gold em PySpark e Delta Lake com SCD Type 2 via Delta MERGE |
| [SCD-Type-2-com-PostgreSQL-e-Python](https://github.com/dgeison/SCD-Type-2-com-PostgreSQL-e-Python) | Pipeline ETL completo de SCD Tipo 2 — detecção de mudanças, Point-in-Time Joins |
| [lab-etl-pyspark](https://github.com/dgeison/lab-etl-pyspark) | Pipeline ETL profissional com PySpark, validação de qualidade e config YAML |
| [streaming-clickstream-flink](https://github.com/dgeison/streaming-clickstream-flink) | Streaming de clickstream com Apache Flink |
| [apache-flink-sql-docker](https://github.com/dgeison/apache-flink-sql-docker) | Apache Flink SQL Client com Docker |
| [apache-kafka-elasticsearch](https://github.com/dgeison/apache-kafka-elasticsearch) | Ingestão em streaming com Kafka e indexação em Elasticsearch |
| [puc-processamento-distribuido-nyc-taxi](https://github.com/dgeison/puc-processamento-distribuido-nyc-taxi) | Processamento distribuído do dataset NYC Taxi — trabalho da pós PUC Minas |
| [esteira_cicd](https://github.com/dgeison/esteira_cicd) | Esteira de CI/CD (GitHub Actions) para app Python de dados |
| [mvp-eleicoes-analytics](https://github.com/dgeison/mvp-eleicoes-analytics) | Analytics de dados eleitorais |
| [insights-varejo-ia](https://github.com/dgeison/insights-varejo-ia) | Análise de produtos, sentimentos e custos com IA (varejo) |
| [EcoMart-AI-Customer-Assistant](https://github.com/dgeison/EcoMart-AI-Customer-Assistant) | Assistente de atendimento e-commerce com OpenAI |
| [ddd-fastapi](https://github.com/dgeison/ddd-fastapi) | Monólito Modular com FastAPI e DDD |
| [aeronave-graphql-api](https://github.com/dgeison/aeronave-graphql-api) | API GraphQL |
| [microsservicos-checkout-api](https://github.com/dgeison/microsservicos-checkout-api) | Microsserviços de checkout |
| [lab-microservicos-kafka](https://github.com/dgeison/lab-microservicos-kafka) | Microsserviços com Kafka |
| [finbank-ledger-api](https://github.com/dgeison/finbank-ledger-api) | API bancária educacional (Node/Express) |
| [TrainOps-PostgreSQL](https://github.com/dgeison/TrainOps-PostgreSQL) / [TrainOps](https://github.com/dgeison/TrainOps) | Gestão de academia — evolução de JSON para PostgreSQL+Docker |

## Ciência de Dados & Engenharia de Dados — estudos

| Repo | Sobre |
|---|---|
| [data-science-estudos](https://github.com/dgeison/data-science-estudos) | Coleção de exercícios pontuais de análise/ciência de dados — 20 subpastas (pandas, estatística, ML, leitura de arquivos, etc.) |
| [lab-airbnb](https://github.com/dgeison/lab-airbnb) | Predição de preços de imóveis Airbnb no Rio de Janeiro |
| curso_engenharia_dados 🔒 | Curso completo de Ciência/Engenharia de Dados (52 módulos: estatística, ML, deep learning, LLMs, grafos, SQL/NoSQL, cloud, Spark) |
| curso-aws-engenharia-dados 🔒 | Curso de Engenharia de Dados com foco em AWS (18 módulos: S3, Redshift, MongoDB, Hadoop, Spark, Kinesis, Glue/Athena) |

## Fundamentos / cursos de programação

| Repo | Sobre |
|---|---|
| [exercicios_python](https://github.com/dgeison/exercicios_python) | Exercícios de Python |
| [fastapi_2025](https://github.com/dgeison/fastapi_2025) | Estudos de FastAPI |
| [projeto-livro-fastapi](https://github.com/dgeison/projeto-livro-fastapi) / [projeto-livros-fastapi](https://github.com/dgeison/projeto-livros-fastapi) | API de livros com FastAPI |
| [template-saas](https://github.com/dgeison/template-saas) | Template base para SaaS |
| [agendapro](https://github.com/dgeison/agendapro) / [lab-agendapro](https://github.com/dgeison/lab-agendapro) | Sistema de agendamento |
| [curso_intensivo_python_3rd](https://github.com/dgeison/curso_intensivo_python_3rd) *(fork)* | Recursos do livro Python Crash Course, 3rd ed. |

## Bases de conhecimento pessoais

| Repo | Sobre |
|---|---|
| llm-wiki 🔒 | Base de conhecimento sobre SaaS e IA, mantida por LLM (método Karpathy) |

## Produtos e sites de clientes/campanhas (não é portfólio técnico)

subtenentegonzaga-site-2026 🔒 · denisebrasil4440-site 🔒 · [lena-legal-pages](https://github.com/dgeison/lena-legal-pages) · agencia-influenciadoras-ia 🔒 · catalogo-streaming 🔒 · abba_bot 🔒 · cloudarr-core 🔒 · openclaw-workspace-backup 🔒 · patient-binturong-nudge 🔒

🔒 = repositório privado
