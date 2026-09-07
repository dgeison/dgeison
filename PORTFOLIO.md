# Índice de repositórios

Catálogo de todos os repositórios, organizado por tipo. Serve como camada de
busca sobre o histórico técnico — tanto para quem visita o perfil quanto como
referência rápida em sessões futuras com LLM.

Última atualização: 2026-09-07.

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
| [data-science-estudos](https://github.com/dgeison/data-science-estudos) | Coleção de exercícios pontuais de análise/ciência de dados (pandas, estatística, ML, leitura de arquivos, Spark, etc.) |
| [lab-airbnb](https://github.com/dgeison/lab-airbnb) | Predição de preços de imóveis Airbnb no Rio de Janeiro |
| curso_engenharia_dados 🔒 | Curso completo de Ciência/Engenharia de Dados (52 módulos: estatística, ML, deep learning, LLMs, grafos, SQL/NoSQL, cloud, Spark) |
| curso-aws-engenharia-dados 🔒 | Curso de Engenharia de Dados com foco em AWS (18 módulos: S3, Redshift, MongoDB, Hadoop, Spark, Kinesis, Glue/Athena) |
| [spark-estudos-diversos](https://github.com/dgeison/spark-estudos-diversos) | Coleção de exercícios PySpark (NLP, recomendação, classificação, regressão) + configs de cluster local |
| [databricks-pyspark-udemy](https://github.com/dgeison/databricks-pyspark-udemy) | Curso completo de Databricks/PySpark — notebooks, Delta Lake, dashboards |
| puc-minas-pos-graduacao 🔒 | Trabalhos e notebooks da pós-graduação em Engenharia de Dados (PUC Minas), 2022 e 2025 |
| puc-praticas-streaming-kafka-flink 🔒 | Práticas de streaming (Kafka + Flink) da disciplina de processamento de fluxos, PUC Minas |

## Backend / APIs — estudos

| Repo | Sobre |
|---|---|
| [fastapi](https://github.com/dgeison/fastapi) | Estudos de FastAPI (fast_zero) |
| [fastapi-autenticacao-alura](https://github.com/dgeison/fastapi-autenticacao-alura) | API FastAPI com middleware de autenticação, rotas e modelos |
| [django-blog-estudo](https://github.com/dgeison/django-blog-estudo) | App Django (blog + home) |
| [estudos-arquitetura-software](https://github.com/dgeison/estudos-arquitetura-software) | Estudos de arquitetura modular e DDD/hexagonal |
| [hardcoded-guide](https://github.com/dgeison/hardcoded-guide) | Guia autoral didático sobre credenciais hardcoded (o que não fazer) |
| [sql-estudos](https://github.com/dgeison/sql-estudos) | Coleção de exercícios SQL (PL/pgSQL, análise de vendas fictícia) |
| [sql_course](https://github.com/dgeison/sql_course) | Curso de SQL |
| [sql_book](https://github.com/dgeison/sql_book) | Exercícios de livro de SQL |
| [oreilly_getting_started_with_sql](https://github.com/dgeison/oreilly_getting_started_with_sql) | Exercícios do livro "Getting Started with SQL" (O'Reilly) |
| [docker-estudos](https://github.com/dgeison/docker-estudos) | Exercícios pontuais de Docker/docker-compose |

## Frontend — estudos

| Repo | Sobre |
|---|---|
| [frontend-estudos](https://github.com/dgeison/frontend-estudos) | Coleção de desafios HTML/CSS |
| [javascript-estudos-diversos](https://github.com/dgeison/javascript-estudos-diversos) | Curso básico de JavaScript (DOM, AJAX) |
| [01-fundamentos-reactjs](https://github.com/dgeison/01-fundamentos-reactjs) | Fundamentos de React |
| [react-02-motores-do-react](https://github.com/dgeison/react-02-motores-do-react) / [react-03-fundamentos-reactjs-ts](https://github.com/dgeison/react-03-fundamentos-reactjs-ts) / [react-04-estrutura-de-aplicacao](https://github.com/dgeison/react-04-estrutura-de-aplicacao) | Trilha de estudos React + TypeScript (Rocketseat) |
| [react-desafio-trilha](https://github.com/dgeison/react-desafio-trilha) / [react-desafio-trilha-componentizando](https://github.com/dgeison/react-desafio-trilha-componentizando) | Desafios da trilha React |
| [letmeask_cobranca](https://github.com/dgeison/letmeask_cobranca) | App de perguntas ao vivo (React + Firebase) |
| [ignews-rocket](https://github.com/dgeison/ignews-rocket) | App de assinaturas (Next.js) |
| [ecommerce-node](https://github.com/dgeison/ecommerce-node) | E-commerce em Node.js |
| [foodfy](https://github.com/dgeison/foodfy) | App de receitas (Node + Nunjucks) |
| [rentalx](https://github.com/dgeison/rentalx) | Sistema de aluguel de carros (Node + TypeORM + Docker) |
| [todo-js](https://github.com/dgeison/todo-js) | To-do list (Node + Jest) |
| [worldtrip](https://github.com/dgeison/worldtrip) | Site de viagens (Next.js) |

## React Native — estudos

| Repo | Sobre |
|---|---|
| [rn-ignite-todo-desafio-02](https://github.com/dgeison/rn-ignite-todo-desafio-02) / [rn-ignite-template-todo](https://github.com/dgeison/rn-ignite-template-todo) | Desafios de to-do list (Ignite/Rocketseat) |
| [rn-myskills](https://github.com/dgeison/rn-myskills) | App de habilidades (React Native) |

## Python — exercícios e cursos avulsos

| Repo | Sobre |
|---|---|
| [python-estudos-diversos](https://github.com/dgeison/python-estudos-diversos) | Coleção grande de exercícios pontuais de Python (padrões de projeto, orientação a objetos, scripts avulsos) |
| [python-curso-alura](https://github.com/dgeison/python-curso-alura) | Coleção de submódulos de curso Python da Alura (datetime, estruturas de dados, jogos) |
| [python-orientacao-objeto](https://github.com/dgeison/python-orientacao-objeto) | Exercícios de orientação a objetos em Python |
| [cursopython2023](https://github.com/dgeison/cursopython2023) | ~300 exercícios "aula a aula" de curso de Python |
| [curso-josue-python](https://github.com/dgeison/curso-josue-python) | Exercícios de Python (estruturas de dados, funções) |
| [100-days-of-python](https://github.com/dgeison/100-days-of-python) | Desafio 100 dias de Python |
| [python-introducao-a-collections](https://github.com/dgeison/python-introducao-a-collections) / [python-introducao-a-collections2](https://github.com/dgeison/python-introducao-a-collections2) | Exercícios de collections em Python |
| [python-chatbot-openai-curso03](https://github.com/dgeison/python-chatbot-openai-curso03) | Chatbot com API da OpenAI |
| [livroescd](https://github.com/dgeison/livroescd) | Exercícios de estrutura de dados |
| [jogo_da_forca](https://github.com/dgeison/jogo_da_forca) | Jogo da forca em Python |
| [file_finder](https://github.com/dgeison/file_finder) | Utilitário de busca de arquivos |
| [pipeline_python](https://github.com/dgeison/pipeline_python) | Pipeline de dados combinando Python e OO |
| [python-curso03](https://github.com/dgeison/python-curso03) | Curso de Python |
| [notas-musicais](https://github.com/dgeison/notas-musicais) | Exercício de notas musicais |
| [desenvolvimento_orientado_em_testes](https://github.com/dgeison/desenvolvimento_orientado_em_testes) | Exercícios de TDD |
| [bytebank](https://github.com/dgeison/bytebank) | App bancário (Python) |
| [robo-cripto](https://github.com/dgeison/robo-cripto) | Robô de trading (Binance API) |
| [estudos-go](https://github.com/dgeison/estudos-go) | Fundamentos de Go + projeto DDD/clean code |
| [rainbow-remote](https://github.com/dgeison/rainbow-remote) | Exercício de aprendizado de Git (remotes, branches) |

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
