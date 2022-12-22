# Homebanking
Java Spring boot OpenAPI Micro services 


docker run -p 127.0.0.1:3306:3306  --name mdb -e MARIADB_ROOT_PASSWORD=root -d mariadb:latest

docker exec -it mdb mariadb --user root -proot

CREATE DATABASE Account;

npm install
C:\projects\eval\training_nka\homebank\bank-ui>npm start --open


KAFKA:


kafka-topics --bootstrap-server `grep "^\s*bootstrap.server" $HOME/.confluent/java.config | tail -1` --command-config $HOME/.confluent/java.config --topic test1 --create --replication-factor 3 --partitions 6

kafka-topics --bootstrap-server localhost:9092  --topic transaction --create --replication-factor 1 --partitions 6


Backend
Application
  SpringBoot
  Code
  Lombok
  MapStruct
  API 
  OpenAPI
  RESTful
  FeignClient (required)
  WebClient (optional)
  Datastore
  Spring Data
  Elasticsearch
  Oracle
  MariaDB
  H2
  Redis/Redisson

  JUnit 5
  Mockito
  Hamcrest
  MockMvc
  AssertJ
  Spring Cloud Contract - to test functionalities between microservices
  Integration testing: testcontainers
  Spring integration
  Rabbit MQ
  UI
  Angular 12
  Material design
  Bootstrap
  ag-grid
  ngrx
  DevOps
  Git 

