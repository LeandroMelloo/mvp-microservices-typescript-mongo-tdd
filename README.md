# mvp_microservices_typescript_mongo_tdd
MVP de micro-serviço com TypeScript, Mongo e TDD

# Regra de negocio da MVP
- Enviar emails pra uma lista de uma forma fácil

# Requisitos Funcionais
- Importar uma lista em CSV e relacionar ela com uma tag;
- Enviar mensagem para uma ou mais tags;
- Listar inscritos em uma ou mais tags;
- Visualização do progresso de envio (concluido/não-concluido);

# Requisitos Não-Funcionais
- Utilizar o Amazon SES
- Utilizar MongoDB
- Utilizar Express
- Utilizar serviço de mensageria (Redis)

# Regra de Negocio
- Na importação, se a tag não existir ela deve ser criada
- Na importação, se o usuário já existir, só vamos veicula-lo com a tag
- A importação deve permitir múltiplas tags

# MVP
Tem que estar no ar em 1 semana

# Docker
docker-compose up

# Nest.js
nest new name_project
nest g module name_module
nest g service name_service
nest g controller name_controller
nest g resource name_resource

# Oque é o Nest.js?
- Framework Node Fullstack MVC WEB
- Lançado em 2017 pelo Kamil Mysliwiec
- Construído em Typescript
- Usa as ideias de arquitetura do Angular
- Foco em microserviços

# Quais as vantagens do Nest.js?
- Coc (Convention Over Configuration)
- Uasr Typescript no desenvolvimento
- Arquitetura escalável
- Grande compatibilidade com sistemas:
    - Banco de Dados: Mysql, PostgreSQL, MongoDB, etc.
    - Websockets
    - Microserviços: Redis, RabbitMQ, Kafka, gRPC, CQRS e etc.
