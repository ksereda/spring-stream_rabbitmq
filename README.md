# spring-stream_rabbitmq

I use Spring Cloud Stream to connect two microservices through a message broker like RabbitMQ.

1) Start docker-compose.yml file (RabbitMQ)
2) Start publisher app and subscriber app separately
3) Open a browser and send a message to http://localhost:8081/sendMessage 
like: http://localhost:8081/sendMessage/hello_java
