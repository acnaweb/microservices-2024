# Microservice and Web Engineering - 3SI/23

## Check Point 1/1º semestre - Prof. Antonio Carlos de Lima Júnior

### Instruções

- Prazo de entrega: __16/03__
- O checkpoint deverá ser desenvolvido em 1 ou 2 pessoas
- Github, nome do repositorio para cada membro: __fiap-2023-checkpoint1__
- Cada membro deve ter o projeto em seu próprio repositório no Github até a data de entrega.
- A formalização da entrega deverá ser realizada por um upload de um arquivo TXT na plataforma FIAP, área de upload de arquivos para o Checkpoint.

> - Pessoa 1 - Maria - https://github.com/maria/fiap-2023-checkpoint1
> - Pessoa 2 - João - https://github.com/joao/fiap-2023-checkpoint1

### Conteúdo

#### 1. (_1 ponto_) - Criar um projeto Java usando Spring Boot:

- Project: 		Maven Project
- Language: 	Java
- Spring Boot: 	2.X

Project Metadata

> - Group: 	br.com.fiap
> - Artifact: 	checkpoint1
> - Name: 	checkpoint1
> - Description: Checkpoint 1
> - Package Name: br.com.fiap.checkpoint1
> - Packaging: 	Jar
> - Java: 		8/11

#### 2. (_0,5 ponto_) - Inserir dependecias de Spring Web
#### 3. (_0,5  ponto_) - Inserir dependecias de Spring Data
#### 4. (_0,5  ponto_) - Inserir dependecias de H2 Database
#### 5. (_0,5 ponto_) - Incluir a documentação online do projeto (Swagger/OpenAPI)

#### 5. (_1  ponto_) - Criar a classe Empregado e torná-la uma entidade de banco de dados.

```
Empregado:

- codigoEmpregado: Long (atributo identificador)
- nome: String
- endereco: String
```

#### 6. (_2 pontos_) - Implementar um endpoint POST para incluir Empregado

#### 7. (_2 pontos_) - Implementar um endpoint PUT para alterar Empregado

#### 8. (_2 pontos_) - Implementar um endpoint GET para listar todos os  Empregados

