# Trabalho Spring Boot

Projeto simples de cadastro de produtos feito em Java + Spring Boot para aplicação web

# Setting up
O projeto funciona na porta 8080, porém é possivel mudar a porta utilizando o comando server.port = <numero_da_porta> para persolizar a porta usada. O banco de dados utilizado é o PostgreSQL, ele se conecta pela porta 5432, usando o Username "posrgres" e o Password "admin". Deve se criar um database chamado "produtos" antes de iniciar a API, sua URL padrão da API é "/produtos"

# Outras dependecias utilizadas:
É possivel acessar a documentação em Swagger pelo url "http://localhost:8080/swagger-ui.html#/". O Flywaydb também é utilizado para manutenção de scripts SQL
