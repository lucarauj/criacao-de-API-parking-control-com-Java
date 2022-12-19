[![NPM](https://img.shields.io/npm/l/react)](https://github.com/lucarauj/criacao-de-API-parking-control-com-Java/blob/main/LICENSE)

<h1 align="center"> Criação de API Parking Control com Java </h1>

<p align="center"><img width="200px" src="https://github.com/lucarauj/assets/blob/main/ApiJavaSpring.png" /></p>

### ❌ Criação do projeto base no [Spring Initializr](https://start.spring.io/) com as seguintes dependências:
- Spring Web
- Spring DATA JPA
- Validation
- PostgreSQL

### ❌ Utilizando o Postman:

- POST
<img width="800px" src="https://github.com/lucarauj/criacao-de-API-parking-control-com-Java/blob/main/images/POST.png"/>

- GET ALL
<img width="800px" src="https://github.com/lucarauj/criacao-de-API-parking-control-com-Java/blob/main/images/GET%20ALL.png"/>

- GET ONE
<img width="800px" src="https://github.com/lucarauj/criacao-de-API-parking-control-com-Java/blob/main/images/GET%20ONE.png"/>

- PUT
<img width="800px" src="https://github.com/lucarauj/criacao-de-API-parking-control-com-Java/blob/main/images/PUT.png"/>

- DELETE
<img width="800px" src="https://github.com/lucarauj/criacao-de-API-parking-control-com-Java/blob/main/images/DELETE.png"/>

### 📝 Anotações utilizadas no projeto:

- @GetMapping: usada para mapear solicitações HTTP GET em métodos manipuladores específicos;
- @Entity: utilizada para informar que uma classe também é uma entidade;
- @Table: usada para especificar a tabela principal da entidade atualmente anotada;
- @Id: especifica o identificador da entidade. Uma entidade deve sempre ter um atributo identificador, que é usado ao carregar a entidade em um determinado contexto de persistência;
- @GeneratedValue (GenerationType.AUTO): deixa com o provedor de persistência a escolha da estratégia mais adequada de acordo com o banco de dados;
- @Column: usada para especificar o mapeamento entre um atributo de entidade básico e a coluna da tabela de banco de dados;
- @Repository: serve para definir uma classe como pertencente à camada de persistência;
- @Service: marca uma classe Java que executa algum serviço;
- @RestController: marca a classe como um controlador onde cada método retorna um objeto de domínio em vez de uma visão;
- @CrossOrigin: ativa a comunicação entre domínios para os métodos manipuladores de solicitações;
- @NotBlank: um atributo do tipo String não pode ser nulo e nem vazio;
- @Size: confere se a quantidade de elementos está entre o mínimo e o máximo, suportando tipos como: Strings, Collections, Maps e arrays;
- @PostMapping: usada para mapear solicitações HTTP POST em métodos específicos de manipulador;
- @RequestBody: indica que o valor do objeto virá do corpo da requisição;
- @Valid: indica que o valor do objeto virá do corpo da requisição;
- @Transactional: utilizada nos métodos que precisam de transação;
- @PathVariable: indica que o valor da variável virá de uma informação da rota;
- @DeleteMapping: usada para mapear solicitações HTTP DELETE em métodos manipuladores específicos;
- @PutMapping: usada para mapear solicitações HTTP PUT em métodos manipuladores específicos;
- @Configuration: define uma classe como fonte de definições de beans;
- @Bean: utilizada em métodos de uma classe, geralmente marcada com @Configuration, indicando ao Spring Framework que deve invocar aquele método e gerenciar o objeto retornado por ele;
- @Primary: usada quando existem dois métodos anotados com @Bean que retornam o mesmo tipo de objeto, informando qual deles será injetado por padrão quando for solicitado;
- @PageableDefault: permite que sejam informados parâmetros default de paginação e ordenação;

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:
<div style="display: inline_block"><br>
<img align="center" alt="Lucarauj-Java" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg">
<img align="center" alt="Lucarauj-Postman" height="50" width="90" src="https://github.com/lucarauj/assets/blob/main/postman.png">
<img align="center" alt="Lucarauj-Spring" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg">
<img align="center" alt="Lucarauj-Postgresql" height="40" width="50" src="https://github.com/lucarauj/assets/blob/main/postgresql.svg">
</div>

## Aluno

Lucas Araujo

<a href="https://www.linkedin.com/in/lucarauj"><img alt="lucarauj | LinkdeIN" width="40px" src="https://user-images.githubusercontent.com/43545812/144035037-0f415fc7-9f96-4517-a370-ccc6e78a714b.png" /></a>

