# CRUD

API RESTful Java

## Recursos utilizados

jpa,
spring-web,
postgresql,
validation,
hateoas para hipermídias,

### Conexão com postgres
<br>

**Define a URL de conexão ao banco de dados PostgreSQL.** <br>
spring.datasource.url= jdbc:postgresql://localhost:5432/products-api
<br>

**Define o nome de usuário que será utilizado para acessar o banco de dados.** <br>
spring.datasource.username=usuario
<br>

**Define a senha correspondente ao usuário para acessar o banco de dados.** <br>
spring.datasource.password=senha
<br>

**Configura o Hibernate, um framework de ORM (Object-Relational Mapping), para permitir a criação de LOBs (Large Objects).** <br>
spring.jpa.properties.hibernate.jdbc.lob.non_contextual_creation=true
