# Sobre o projeto

https://course-javasb-ab828fa92814.herokuapp.com/

 Esta é uma aplicação back-end construída durante aulas do professor Nelio Alaves, curso desonvolvido pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em criar projeto de web services com Spring Boot e JPA / Hibernate, sistema de gerenciamento de pedidos, com cadastro de usuarios, lançamento de itens, pagamentos.

## Objetivos

- Criar projeto Spring Boot Java
- Implementar modelo de domínio
- Estruturar camadas lógicas: resource, service, repository
- Configurar banco de dados de teste (H2)
- Povoar o banco de dados
- CRUD - Create, Retrieve, Update, Delete
- Tratamento de exceções

## Modelo conceitual
![Modelo Conceitual](https://github.com/haylonmosinhodev/assets/blob/main/domain%20model.jpg)


# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- H2
- Apache Tomcat


## Implantação em produção
- Back end: Heroku  
- Banco de dados: Postgresql
- Aos estutandantes matriculados regulamente em instituição de ensino, estou usando creditos disponibilizados pelo GitHub Student Developer Pack, 300$ para uso no Heroku em 2 anos.

## Back end
Pré-requisitos: Java 17

# Como executar o projeto
- Localmente com H2-CONSOLE = Nos arquivos do projeto vá para o pacote src/main/resources/application.properties e altere para perfil de teste (spring.profiles.active=test).
  Na barra de endereço do navegador lance: localhost:8080/h2-console.


- Utilizar o Postman para fazer requisições ao sistema implantado no Heroku .
- Exemplo de cadastro de usuario:
```json
{
    "name" : "Haylon Mosinho",
    "email": "haylon@gmail.com",
    "password": "123456",
    "phone": "99999999999"
}
```
  
![Cadastrando Usuario](https://github.com/haylonmosinhodev/assets/blob/main/postman%20get%20usuario.jpg)

- https://course-javasb-ab828fa92814.herokuapp.com/users

```bash
# clonar repositório
git clone https://github.com/haylonmosinhodev/workshop-springboot3-jpa.git
```
 
# Autor

Haylon Mosinho

https://www.linkedin.com/in/haylonmosinho/



