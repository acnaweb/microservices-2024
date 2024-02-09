## Microservice and Web Engineering

#### [Apresentações - Quem sou eu? Quem é você?](/apresentacao.md)

----

#### Projetos

| Repositórios | 
|----|
| [Repositório de conteúdos e acompanhemnto de aulas](https://github.com/acnaweb/microservices-fiap) |
| [Projeto de Estudo de Java](https://github.com/acnaweb/study-java-fiap-2023) |
| [Projeto de Estudo de API com Spring](https://github.com/acnaweb/study-api) |
| [Projeto de Estudo de Thymeleaf](https://github.com/acnaweb/study-thymeleaf) |
| [Projeto Ping](https://github.com/acnaweb/ping) |
| [Projeto E-Commerce](https://github.com/acnaweb/ecommerce) |

----

#### Aulas

2º Semestre

__28/09__

- Lombok - https://www.baeldung.com/lombok-ide
- Lombok Intro - https://www.baeldung.com/intro-to-project-lombok

__03/08__

- Docker
- Docker Registry 

__10/08__

- Docker
- Docker Registry 

1º Semestre

__09/02__

- [x] Criar conta no Postman
- [Postman](https://www.postman.com/)
- [x] Client API com Postman
 - API Pública - [Via CEP](https://viacep.com.br/)
- [JSON](https://www.json.org/json-en.html)
- [JSON Viewer](http://jsonviewer.stack.hu/)

__16/02__

- API Client [Postman](https://www.postman.com/)
- [X] HTTP 
- [Protocolo HTTP Overview](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Overview)
- [X] NodeJS [NVM](https://github.com/nvm-sh/nvm)
- [X] [NodeJS](https://nodejs.org/en/download/) 
- [X] [JSON Server](https://www.npmjs.com/package/json-server)

__23/02__

- [Portas HTTP] (https://pt.wikipedia.org/wiki/Lista_de_portas_dos_protocolos_TCP_e_UDP)
- Criar conta no Github 
 - [Github](https://github.com/)
 - Aprender o básico de [Git](https://www.alura.com.br/artigos/comecando-com-git-aprendendo-versionar)
- Projeto study-java
- [Links apresentados na aula](/aulas/20232302.md)
- Criar repositório do projeto no Github
- Instalar o [Git Client](https://www.alura.com.br/conteudo/git-github-controle-de-versao--amp)
- URI (Uniform Resource Identifier)
    - URL (Uniform Resource Locator) - esquema ou protocolo://domínio:porta/path/resource?query_string
    - URN (Uniform Resource Name) - Ex: nome de uma pessoa
__02/03__

- [Spring](/conceitos/spring.md)
- [Maven](/conceitos/maven.md)
- [12Factors](https://github.com/acnaweb/12factors)


__09/03__

- [Spring](/conceitos/spring.md)
- [Design Patterns](https://www.tutorialspoint.com/design_pattern/index.htm)
- [H2 Database](https://www.h2database.com/html/main.html)

__16/03__

- [Git](/conceitos/git.md)
- https://education.github.com/git-cheat-sheet-education.pdf

__30/03__

- [Java Method Reference](https://www.baeldung.com/java-method-references)
- [DTO Pattern](https://www.baeldung.com/java-dto-pattern)

__13/04__

- [Spring profile](https://docs.spring.io/spring-boot/docs/1.2.0.M1/reference/html/boot-features-profiles.html)
- [Spring: alterando a porta padrão](https://www.baeldung.com/spring-boot-change-port)
- [@ResponseBody](https://www.baeldung.com/spring-request-response-body)
- [spring-boot-devtools](https://www.baeldung.com/spring-boot-devtools)
- Data/hora em Java
    - https://www.devmedia.com.br/trabalhando-com-as-classes-date-calendar-e-simpledateformat-em-java/27401
    - https://www.w3schools.com/java/java_date.asp
    - https://www.baeldung.com/java-8-date-time-intro

__20/04__

- [Spring Starters](https://docs.spring.io/spring-boot/docs/current/reference/html/using.html#using.build-systems.starters)
- [Spring profile/data.sql](https://www.baeldung.com/spring-boot-data-sql-and-schema-sql)
- [Oracle x Java: Type mapping](https://docs.oracle.com/cd/A97335_02/apps.102/a83724/basic3.htm)
- LocalDate/LocalDateTime

__27/04__

- [Spring Framework](https://spring.io/)
- [Json Path](https://jsonpath.com/)
- Sequence
- [ResponseEntity](https://www.baeldung.com/spring-response-entity)
    - [Métodos HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods)
    - [Status HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Status)

```
Códigos de retorno HTTP

    200: OK
        Consultas
    201: Registro criado
        Inserção de registros
    202: Recurso em processamento
    400: Entrada inválida
        Exemplo: O usuário não preencheu um campo obrigatório
    401: Sem autenticação ou autenticação inválida
    403: Sem permissão no recurso
    404: Registro inexistente
        Exemplo: Busca de um usuário por ID
    422: Erros de regras de negócio
        Exemplo: A porcentagem de entrada deve ser maior que 15%
    500: Erro inesperado
```
__04/05__

- [Thymeleaf](www.thymeleaf.org)

__25/05__

- [MVC](/conceitos/mvc.md)
- [Thymeleaf](www.thymeleaf.org)


2023-2

- [Mapper](https://www.baeldung.com/java-dto-pattern)
- PUT path param + DTO
- Variáveis de ambientes (Secrets)
- Datas: LocalDate/LocalDatetime
- [Validação de DTO](https://www.javaguides.net/2021/04/spring-boot-dto-validation-example.html)

    - @NotNull validates that the annotated property value is not null.
    - @Size validates that the annotated property value has a size between the attributes min and max; can be applied to String, Collection, Map, and array properties.
    - @Min validates that the annotated property has a value not smaller than the value attribute.
    - @Max validates that the annotated property has a value no larger than the value attribute.
    - @Email validates that the annotated property is a valid email address.
    - @NotEmpty validates that the property is not null or empty; can be applied to String, Collection, Map, or Array values.
    - @NotBlank can be applied only to text values and validates that the property is not null or whitespace.
- [Handler Exception](https://www.baeldung.com/exception-handling-for-rest-with-spring)
- JPA - Relacionamentos/Queries
- Autenticação e Autorização
- Paginação
- Docker
- Deploy Cloud

DevOps

- Testes Unitários
- Gitlab Flow
- CI

#### Próximos passos

- [Mapper](https://www.baeldung.com/java-dto-pattern)
- [Arquitetura de Microserviços](https://microservices.io/)
- [ ] Criar gratuita conta no AWS
- [AWS](https://aws.amazon.com/pt/)
- [ ] Instalar gerenciador de Java [SDKMain](https://sdkman.io/install)
- [ ] Instalar Java 11 por [download](https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html) ou [SDKMain](https://sdkman.io/usage)
- [ ] [IntelliJ](https://www.jetbrains.com/pt-br/idea/) ou [STS](https://spring.io/tools)
- [ ] Instalar [Docker](https://www.docker.com/) 

#### O Projeto

Desenvolver um sistema de e-commerce com produtos, clientes, consultas de endereço por CEP e pedidos, realizando notificações por email.

- Java 11 
- [Spring Initializer]
- RDBMS - H2 (dev) e Oracle (prd)
- Design Patterns - Command, Builder, Factory
- Mensageria - Kafka
- Container - Docker 
- Cloud Azure/AWS/Heroku
- Repositório de código - github.com
- Frontend MVC - [Thymeleaf](https://www.thymeleaf.org/)
- Frontend SPA - [React](https://reactjs.org/)
- WebServer - [NodeJS](https://nodejs.org/en/) 
- Testes Unitários - [JUnit](https://junit.org/junit5/)

#### Cursos Alura

- (https://cursos.alura.com.br/course/jdbc-dao-persistencia)
- (https://cursos.alura.com.br/course/java-jpa-consultas-avancadas-performance-modelos-complexos)
- (https://cursos.alura.com.br/course/servlets-fundamentos-programacao-web-java)
- (https://cursos.alura.com.br/course/servlet-autenticacao-autorizacao-mvc)
- (https://cursos.alura.com.br/course/microsservicos-padroes-projeto)
- (https://cursos.alura.com.br/course/fundamentos-microsservicos-aprofundando-conceitos)
- (https://cursos.alura.com.br/course/microsservicos-implementando-java-spring)
- (https://cursos.alura.com.br/course/spring-boot-3-desenvolva-api-rest-java)
- (https://cursos.alura.com.br/course/spring-boot-aplique-boas-praticas-proteja-api-rest)
- (https://cursos.alura.com.br/course/microservices-spring-cloud-service-registry-config-server)
- (https://cursos.alura.com.br/course/microsservicos-pratica-iac-cdk-deploy-aws)


#### Livros
- [Spring Boot](https://www.casadocodigo.com.br/products/livro-spring-boot)

#### Links úteis
- [Spring Initializr](https://start.spring.io/)
- [API Rest](https://blog.betrybe.com/desenvolvimento-web/api-rest-tudo-sobre/)
- [eBooks](https://www.kdnuggets.com/2015/09/free-data-science-books.html)




