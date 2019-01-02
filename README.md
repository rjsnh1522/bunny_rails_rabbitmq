## A working example of RabbitMQ, Bunny and Sneaker gem

Two apps communicating over RabbitMQ

CRUD app using RabbitMQ and two rails application

Run each app over a different port (i.e. 3000/3001)

*Blog* is a producer app
*Dashboard* as a consumer app


To run the sneakers worker run **WORKERS=PostsWorker rake sneakers:run** in *dashboard app*

run rake file to setup rabbitmq check **Rakefile** in dashboard app 
**rake rabbitmq:setup**