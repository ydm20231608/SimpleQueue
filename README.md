# Simple demo RabbitMQ using java
## Details
```
  App.java just send the message to the queue, not provide any consumers
  Sender.java provides message consumers to handle messages in the queue
```
## Set up
- Download RabbitMQ, Erlang
- Create maven project https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
- Open RabbitMQ Command Prompt and start rabbitmq server
```
rabbitmq-server start
```

## Step
  1 Run  current file (App.java , Sender.java)\
  2 Check the message at http://localhost:15672/ 
### IDE 
  IntelliJ IDEA
