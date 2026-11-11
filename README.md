# João Victor · Desenvolvedor Backend

Construo APIs e pipelines de dados com Python e Java, com foco em código limpo, testes automatizados e CI. Estou em busca da minha primeira oportunidade como desenvolvedor backend.

📍 Brasil  |  📧 [nevvesdev@gmail.com](mailto:nevvesdev@gmail.com)  |  💼 [LinkedIn](https://www.linkedin.com/in/nevvesdev/)

## Sobre mim

Trabalho há mais de dois anos em operações corporativas em uma empresa de grande porte. Lá aprendi a valorizar regras de negócio, consistência de dados e processos que não podem falhar, e levo essa mentalidade para o código.

Hoje desenvolvo com Java e Spring Boot e uso Python para APIs, automações e pipelines de dados. Cada projeto tem README com diagramas Mermaid, decisões de arquitetura e instruções para rodar com Docker Compose.

## Tecnologias

- **Backend:** Python (FastAPI e Flask), Django, Java 21 e Spring Boot
- **Dados:** Apache Spark, Delta Lake, Databricks, Pandas, SQL
- **Frontend:** Angular (no FinanceFlow, projeto full stack)
- **Mensageria e cache:** Apache Kafka, Redis
- **Banco e infra:** PostgreSQL, Flyway, Docker Compose, GitHub Actions, Linux
- **Testes:** JUnit 5, Testcontainers

## Projetos em Python

- **[pipeline-dados-spark](https://github.com/nevvesdev/pipeline-dados-spark):** pipeline medallion (bronze, silver e gold) com Spark e Delta Lake no Databricks, orquestrado em job e com dashboard. *(em finalização)*
- **[sla-performance-operacional](https://github.com/nevvesdev/sla-performance-operacional):** análise de SLA e performance operacional com Python, Pandas e Databricks. *(em andamento)*
- **[crypto-market-pipeline](https://github.com/nevvesdev/crypto-market-pipeline):** ingestão de candles OHLCV da API pública da Binance e de dados on-chain da Ethereum via RPC, gravados em PostgreSQL e expostos por API FastAPI. *(em andamento)*

## Projeto em andamento

- **[financeflow](https://github.com/nevvesdev/financeflow):** painel de controle financeiro pessoal, full stack com Spring Boot e Angular. Lançamentos, categorias, contas a vencer e alertas agendados.

## Projetos em Java

**APIs e autenticação**
- **[guardian-api](https://github.com/nevvesdev/guardian-api):** autenticação e autorização com JWT (access e refresh token), RBAC e rate limiting com Redis.
- **[open-finance-consent](https://github.com/nevvesdev/open-finance-consent):** gestão de consentimentos inspirada no Open Finance, com Arquitetura Hexagonal e OAuth2.

**Cache e dados**
- **[distributed-cache](https://github.com/nevvesdev/distributed-cache):** consulta de saldo e limite de contas com cache Redis no padrão Cache-Aside.

**Eventos e mensageria**
- **[cqrs-pattern](https://github.com/nevvesdev/cqrs-pattern):** CQRS e Transactional Outbox em dois microsserviços, com eventos publicados no Kafka.
- **[notification-hub](https://github.com/nevvesdev/notification-hub):** notificações orientadas a eventos, com Kafka e Resilience4j.

**Negócio e finanças**
- **[alcada](https://github.com/nevvesdev/alcada):** aprovação de linhas de crédito com Saga orquestrada e requisições idempotentes.
- **[fx-currency-exchange](https://github.com/nevvesdev/fx-currency-exchange):** câmbio e taxas de moedas, pensado para fintechs e bancos digitais, com arquitetura em portas e adaptadores.

## Foco

- APIs REST bem estruturadas, seguras e documentadas, em Java e Python
- Pipelines de dados e automações com processos claros e rastreáveis
- Sistemas orientados a eventos e consistência em ambientes distribuídos
- Testes automatizados, CI e documentação clara
