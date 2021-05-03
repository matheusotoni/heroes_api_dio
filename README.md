# Criando um Gerenciador de Herois
# Demo sobre API da digital innovation one - spring webflux 

## Stack utilizada

* Java8
* spring webflux
* Spring data
* Dynamodb
* Junit
* Sl4j
* Reactor

### Executar dynamo:
- Na pasta em que o jar está baixado: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
- Para listar as tabelas criadas:  aws dynamodb list-tables --endpoint-url http://localhost:8000
- Documentacao gerada pela aplicação: swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html