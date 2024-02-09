# Microservice and Web Engineering - 3SI/23

## Check Point 2/1º semestre - Prof. Antonio Carlos de Lima Júnior

### Instruções

- Prazo de entrega: __02/05__
- O checkpoint deverá ser desenvolvido em até 3 pessoas.
- Github, nome do repositorio para cada membro: __fiap-2023-checkpoint2__
- Cada membro deve ter o projeto em seu próprio repositório no Github até a data de entrega.
- A formalização da entrega deverá ser realizada por um upload de um arquivo TXT na plataforma FIAP, área de upload de arquivos para o Checkpoint.

> - Nome completo Pessoa 1 - RM - https://github.com/pessoa1/fiap-2023-checkpoint2
> - Nome completo Pessoa 2 - RM - https://github.com/pessoa2/fiap-2023-checkpoint2
> - Nome completo Pessoa 3 - RM - https://github.com/pessoa3/fiap-2023-checkpoint2

----

### Conteúdo

O que é o sistema? E-commerce com produtos, clientes, consultas de endereço por CEP e pedidos, realizando notificações por email.

- Tabelas e colunas

> - produtos (*codigo_produto, nome, preco, data_validade, data_garantia, em_estoque)
> - clientes (*codigo_cliente, nome, inscricao_federal, cep)
> - pedidos (*numero_pedido, codigo_cliente, data_pedido)
> - itens_pedidos (*sequencia, numero_pedido, codigo_produto, quantidade, valor_total)

- Classes (model/entity)

> - Produto
> - Cliente
> - Pedido
> - ItemPedido

Criar o projeto Java usando Spring Boot

> - Project: 		Maven Project
> - Language: 	Java
> - Spring Boot: 	2.X ou 3.X

Project Metadata

> - Group: 	br.com.fiap
> - Artifact: 	checkpoint2
> - Name: 	checkpoint2
> - Description: Checkpoint 2
> - Package Name: br.com.fiap.checkpoint2
> - Packaging: 	Jar
> - Java: 		8+

#### Questões 

> 1. (_1 ponto_) - Declarar as classes model/entity seguindo padrão Java (singular) referenciando os nomes de tabelas com @Table
> 2. (_1 ponto_) - Declarar os atributos seguindo padrão Java (singular) referenciando os nomes de colunas com @Column
> 3. (_1 ponto_) - Declarar 4 classes "controllers" para cada classe model/entity
> 4. (_1 ponto_) - Declarar 4 classes "services" para cada classe model/entity
> 5. (_1 ponto_) - Implementar endpoints GET (listar todos), GET (pesquisar por ID), POST (criar), PUT (alterar) e DELETE (excluir) na controller relacionada a model/entity Produto
> 6. (_1 ponto_) - Implementar endpoints GET (listar todos), GET (pesquisar por ID), POST (criar), PUT (alterar) e DELETE (excluir) na controller relacionada a model/entity Cliente
> 7. (_1 ponto_) - Implementar endpoints GET (listar todos), GET (pesquisar por ID), POST (criar), PUT (alterar) e DELETE (excluir) na controller relacionada a model/entity Pedido
> 8. (_1 ponto_) - Implementar endpoints GET (listar todos), GET (pesquisar por ID), POST (criar), PUT (alterar) e DELETE (excluir) na controller relacionada a model/entity ItemPedido
> 9. (_1  ponto_) - Criar Spring profile "prd" para banco de dados Oracle
> 10. (_1 ponto_) - Incluir a documentação online do projeto (Swagger/OpenAPI)

Importante: Necessário o uso de DTOs com respectivos mapeamentos para Entities conforme explicado e praticado em aula.


