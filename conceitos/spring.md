#### Spring Docs 

[Documentação de Spring]

#### Spring Initialzr 

[Spring Initialzr] é utilizado para criar projetos com Sprint Boot

#### Spring Anotations

| Anotação | Objetivo |
| ----- | ----- |
| @Component | Qualquer tipo de bean gerenciado pelo Spring | 
| @Service | Classes com regras de negócio | 
| @Autowired | Injeção de variável anotada | 

| Anotação (Data) | Objetivo |
| ----- | ----- |
| @Entity | Identifica a classe como mapeamento de tabela no BD | 
| @Id | Identifica o atributo que representa a coluna para PK na tabela | 
| @Repository | Classes de acesso a banco de dados | 
| @Column | Altera propriedades da coluna no banco de dados | 
| @Table | Altera o nome da table no banco de dados | 
| @GeneratedValue | Usa uma estratégia para geração automática de número identificador único no atributo | 


| Anotação MVC (request) | Objetivo |
| ----- | ----- |
| @Controller | Classes de recursos que fornecem endpoints | 
| @RequestMapping | Mapear URLs de acesso ao controller e aos métodos | 
| @PathVariable | Extrair da URL um parâmetro incluído como path da URL | 
| @RequestParam | Capturar um parâmetro de consulta (query param) GET | 
| @ModelAttribute | Usado como variável de retorno de métodos | 
| @Valid | Validação de dados de objetos em parâmetros | 


| Anotação API (request) | Objetivo |
| ----- | ----- |
| @RestController | Classes de recursos que fornecem endpoints | 
| @GetMapping | Anota o método para responder como endpoint HTTP GET (select) | 
| @PutMapping | Anota o método para responder como endpoint HTTP PUT (update completo) | 
| @PostMapping | Anota o método para responder como endpoint HTTP POST (insert) | 
| @DeleteMapping | Anota o método para responder como endpoint HTTP DELETE (delete) | 
| @RequestMapping | Mapear URLs de acesso ao controller e aos métodos | 
| @PathVariable | Extrair da URL um parâmetro incluído como path da URL | 
| @RequestParam | Capturar um parâmetro de consulta (query param) GET | 
| @Valid | Validação de dados de objetos em parâmetros | 


#### Spring Data

- [Spring Boot com H2](https://www.baeldung.com/spring-boot-h2-database)
- [Spring Boot Data SQL and Schema](https://www.baeldung.com/spring-boot-data-sql-and-schema-sql)


#### Spring

- [Spring OpenAPI docs](https://www.baeldung.com/spring-rest-openapi-documentation)
- [Spring Profiles](https://docs.spring.io/spring-boot/docs/1.2.0.M1/reference/html/boot-features-profiles.html)


[Spring Initialzr]: <https://start.spring.io/>
[Documentação de Spring]: <https://docs.spring.io/spring-framework/docs/current/reference/html/>


