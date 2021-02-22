# Trabalho Spring Boot

Projeto simples de cadastro de produtos
Feito em Java + Spring Boot para aplicação web

# Setting up
O projeto funciona na porta 8080, porém é possivel mudar a porta utilizando o comando server.port = <numero_da_porta> para persolizar a porta usada
Banco de dados utilizado é o PostgreSQL
O banco se conecta pela porta 5432, usando o Username "posrgres" e o Password "admin"
Deve se criar um database chamado "produtos" antes de iniciar a API
E a URL padrão da API é "/produtos"

# Outras dependecias utilizadas:
Swagger: é possivel acessar a documentação em Swagger pelo url "http://localhost:8080/swagger-ui.html#/"
Flywaydb: utilizado para manutenção de scripts SQL
