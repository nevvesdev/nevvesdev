# João Victor · Desenvolvedor Backend

> Construo APIs e sistemas distribuídos com Java e Spring Boot, com foco em código limpo, testes automatizados e arquiteturas que escalam. **Em busca da minha primeira oportunidade como desenvolvedor backend.**

📍 Brasil &nbsp;|&nbsp; 📧 [nevvesdev@gmail.com](mailto:nevvesdev@gmail.com) &nbsp;|&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/nevvesdev/) &nbsp;|&nbsp; 🎥 [YouTube](https://www.youtube.com/@nevvesdev)

---

## Sobre mim

Desenvolvedor backend em início de carreira, com mais de 2 anos de xp em ambiente corporativo de grande porte, no setor sucroenergético. Nesse contexto aprendi a valorizar regras de negócio, consistência de dados, rastreabilidade e processos que não podem falhar, e levo essa mentalidade para o código.

Aprendo construindo: nos projetos em destaque, a infraestrutura (banco, cache e mensageria) sobe com Docker Compose, e cada um evolui com testes automatizados e CI.

---

## Tecnologias

![Java](https://skillicons.dev/icons?i=java)
![Spring](https://skillicons.dev/icons?i=spring)
![PostgreSQL](https://skillicons.dev/icons?i=postgres)
![Redis](https://skillicons.dev/icons?i=redis)
![Kafka](https://skillicons.dev/icons?i=kafka)
![Docker](https://skillicons.dev/icons?i=docker)

- **Java 21+ e Spring Boot 4:** Spring Web, Spring Data JPA, Spring Security, API REST
- **Autenticação e autorização:** JWT (access e refresh token), OAuth2 Resource Server, RBAC
- **Banco de dados e cache:** PostgreSQL, Flyway, Redis
- **Mensageria:** Apache Kafka
- **Arquitetura e padrões:** Arquitetura Hexagonal, Clean Architecture, CQRS, Saga, Transactional Outbox, Cache-Aside, idempotência, máquina de estados
- **Resiliência:** Resilience4j
- **Testes:** JUnit 5, Mockito, Testcontainers
- **Ferramentas:** Docker e Docker Compose, Maven, Gradle, Git, GitHub Actions, Linux, IntelliJ IDEA, RubyMine, Zed

---

## Padrões aplicados

Padrões de arquitetura que venho aplicando nos projetos deste perfil:

| Padrão | Onde é usado | Problema que resolve |
|---|---|---|
| **Saga (orquestração)** | credit-approval-saga *(em andamento)* | Coordena transações distribuídas entre serviços e compensa falhas parciais |
| **Transactional Outbox** | [open-finance-consent](https://github.com/nevvesdev/open-finance-consent), [cqrs-pattern](https://github.com/nevvesdev/cqrs-pattern) | Garante que a alteração no banco e a publicação do evento aconteçam juntas |
| **CQRS** | [cqrs-pattern](https://github.com/nevvesdev/cqrs-pattern) | Separa leitura e escrita, permitindo modelos otimizados para cada uma |
| **Cache-Aside** | [distributed-cache](https://github.com/nevvesdev/distributed-cache) | Reduz carga no banco mantendo o cache alinhado à fonte de verdade |
| **Idempotência** | [event-driven-banking](https://github.com/nevvesdev/event-driven-banking) | Evita que reprocessamentos dupliquem efeitos |
| **Arquitetura Hexagonal** | [open-finance-consent](https://github.com/nevvesdev/open-finance-consent) | Isola o domínio de frameworks e detalhes de infraestrutura |
| **Resiliência (Resilience4j)** | [notification-hub](https://github.com/nevvesdev/notification-hub) | Tolera falhas em chamadas a dependências externas |

---

## Projetos em destaque

- **[credit-approval-saga](https://github.com/nevvesdev/credit-approval-saga):** fluxo de aprovação de crédito como Saga distribuída, com passos compensatórios e tratamento de falhas parciais. *(em andamento)*
- **[fx-currency-exchange](https://github.com/nevvesdev/fx-currency-exchange):** API de câmbio em tempo real e taxas de moedas, pensada para casos de uso de fintechs e bancos digitais. *(em andamento)*
- **[guardian-api](https://github.com/nevvesdev/guardian-api):** API com autenticação JWT (access e refresh token), RBAC, auditoria de acessos e rate limiting com Redis.
- **[open-finance-consent](https://github.com/nevvesdev/open-finance-consent):** gestão do ciclo de vida de consentimentos do Open Finance Brasil, com Arquitetura Hexagonal, OAuth2 Resource Server com escopos, Transactional Outbox e Testcontainers.
- **[notification-hub](https://github.com/nevvesdev/notification-hub):** microsserviço de notificações orientado a eventos, consumindo Kafka, com Resilience4j, Flyway e testes de integração com Testcontainers.
- **[cqrs-pattern](https://github.com/nevvesdev/cqrs-pattern):** CQRS e Transactional Outbox em dois microsserviços, com publicação de eventos no Kafka por polling (simulando CDC).
- **[event-driven-banking](https://github.com/nevvesdev/event-driven-banking):** sistema bancário com três microsserviços (conta, transferência e notificação) comunicando-se via REST e Kafka, com idempotência e CI no GitHub Actions.
- **[distributed-cache](...):** serviço de saldo e limite de contas com cache Redis no padrão Cache-Aside. *(concluído)*

---

## Foco

- **APIs REST** bem estruturadas, seguras e documentadas
- **Sistemas orientados a eventos** e consistência em ambientes distribuídos
- **Qualidade de código:** testes automatizados, CI e documentação clara

---

Também estudo Go de forma esporádica, focando em sistemas distribuídos e performance, como no [distributed-transaction-coordinator](https://github.com/nevvesdev/distributed-transaction-coordinator).
