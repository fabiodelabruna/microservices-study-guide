# Guia de estudo da Arquitetura de Microservices

Um guia com tópicos sobre o que estudar sobre arquitetura de *microservices* e os projetos do ecossistema *Spring Framework*.

1. [MICROSERVICES](#1-microservices)
2. [PATTERNS](#2-patterns)
3. [ARQUITETURA](#3-arquitetura)
4. [SPRING](#4-spring)
5. [PLUS](#5-plus)


## 1 - MICROSERVICES

Base necessária e conceitos sólidos sobre *microservices*, como modelos de comunicações entre *microservices*, comunicações síncronas e assíncronas, uso de mensageria e eventos, base de dados distribuídas por *microservices* ou compartilhada, sincronia e consistência eventual com dados distribuídos, criação de identificadores universais para dados replicado.

- Fundamentos da Arquitetura
- Princípios de Microservices
- Comunicação Síncrona
- Comunicação Assíncrona
- Mensageria
- Replicação de Dados
- Messages via Commands
- Messages via Events
- Teorema CAP
- Sincronia de Dados
- Dados Distribuídos
- Consistência Eventual
- UUIDs Universais
- Cultura Distribuída
- ‍Alta Disponibilidade
- Comunicação OneToOne
- ‍Comunicação OneToMany
- Consumer/Producer
- Publisher/Subscribe
- Request/Response Síncrono
- Request/Response Assíncrono
- Comunicação Assíncrona One-Way
- Brokers
- Exchanges
- Error Queues
- Resiliência Síncrona
- Resiliência na Comunicação Assíncrona
- Autenticação Distribuída
- JWT


### 2 - PATTERNS

Um conjunto de soluções essenciais para não recriar soluções já conhecidas para arquiteturas de *microservices*.

- Event Driven
- Event Notification Pattern
- Event Carried State Transfer Pattern
- API Gateway Pattern
- API Composition Pattern
- SAGA Pattern
- Cross-Cutting
- Service Registry Discovery
- Global Configuration
- Circuit Breaker
- Log Aggregation
- Controle de Métricas
- Padrão JWT Autenticação
- Modelos Autorização
- Database per Service
- Shared Database
- API RESTful
- Maturidade de Richardson para RESTful
- Padrões de Datas
- ISO 8601-UTC
- Comunicação por Coreografia
- Comunicação por Orquestração
- Broker Pattern
- Mediator Pattern
- Access Token Pattern


### 3 - ARQUITETURA

Como projetar arquitetura de *microservices*, como modelar e conceber sistemas que respondam facilmente a mudanças e modernizações tecnológicas, altamente escaláveis e disponíveis.

Arquitetar soluções e tomar as decisões mais adequadas para cada negócio, compreender quando utilizar ou não determinados *patterns*, a comparação das vantagens e desvantagens de uma ou outra solução e também o uso de ferramentas para criação de fluxos e modelagens arquiteturais.

- Projetar Arquiteturas de Microservices
- Modelar Sistemas Distribuídos
- Definição Arquitetural
- Aplicabilidade dos Patterns
- Modelos Arquiteturais
- Concepção Arquiteturas
- Arquitetar Componentes
- Granularidade dos Microservices
- Divisão dos Microservices
- Layouts da Arquitetura
- Fluxos de processos
- Ferramentas Modelagem
- Arquitetura Hexagonal
- Organização Diretórios
- Boas Práticas Projetos
- Organizar Dados Distribuídos


### 4 - SPRING

Implementação da comunicação entre os *microservices*, das APIs, da mensageria via comandos e eventos, da criação e gestão das bases e modelagens de dados, validações, paginações, filtros, autenticação, autorização nos *microservices* e no *gateway*, as preocupações transversais, entre outros, utilizando os projetos do *Spring Framework*.

- Spring Boot
- Spring Data JPA
- Spring Web
- Spring Validation
- Spring Hateoas
- Spring Security
- Spring AMQP
- Spring Cloud Gateway
- Spring Cloud Netflix Eureka
- Spring Cloud Resilience4j
- Spring Actuator
- Spring Cloud Config
- Spring Utils
- Serializações com Jackson ModelMapper
- Bibliotecas para Filters em API REST
- Customizações de Validações
- APIs
- Spring Framework
- Core Container
- Inversão de Controle
- Injeção de Depêndencia
- Beans
- Métodos Produtores
- Estereótipos do Spring


### 5 - PLUS

Conjunto de conhecimento extra excepcional para a composição de uma arquitetura de *microservices*.

- Observabilidade com ELK
- Métricas de Logs Distribuído
- Deploy Arquitetura de Microservices
- Arquitetura Hexagonal
- Arquitetura em Cloud
- Logs com Elasticsearch
- Logs Estruturados
- Config Ambientes Dev/Prod
