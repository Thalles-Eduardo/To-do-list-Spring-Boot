
<h1 align="center">
  To-do-List
</h1>

<p align="center">
    <img src="https://img.shields.io/static/v1?label=License&message=MIT&color=8257E5&labelColor=000000" alt="License" />
</p>


API para gerenciar uma lista de tarefas, com as opções de CRUD. Nesta implementação é feito a conexão do back-end com o front-end através da biblioteca [Thymeleaf](https://www.thymeleaf.org/documentation.html).


## Tecnologias
 
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring MVC](https://docs.spring.io/spring-framework/reference/web/webmvc.html)
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Html5](https://html.com/document/)
- [JavaScript](https://javascript.info/document)
- [Css3](https://www.w3schools.com/cssref/index.php)

## Práticas adotadas

- SOLID, DRY, YAGNI, KISS
- API REST
- Consultas com Spring Data JPA
- Injeção de Dependências

## Como Executar

- Clonar repositório git
```bash
git clone https://github.com/Thalles-Eduardo/To-do-list-Spring-Boot
```
- Copiar as pastas "static" e "templates"
```bash
Copy-Item -Path "Front_End\static","Front_End\templates" -Destination "Back_End\task\src\main\resources" -Recurse
```
- Entrar na pasta para execução
```bash
cd Back_End
cd task
```

- Executar a aplicação:
```bash
./mvnw spring-boot:run
```

A API poderá ser acessada em [localhost:8080/tasks](http://localhost:8080/tasks).

## API Endpoint

![image](https://github.com/Thalles-Eduardo/To-do-list-Spring-Boot/assets/69612509/3e398119-5fbe-4cb2-a698-0f888971a563)


# Author

Thalles Eduardo Dias da Silva

- [Linkedin](https://linkedin.com/in/thalles-eduardo-7297a6237)
