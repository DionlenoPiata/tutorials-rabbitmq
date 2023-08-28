This tutorial assumes RabbitMQ is installed and running on localhost on the standard port (5672). In case you use a different host, port or credentials, connections settings would require adjusting.

We can run RabbitMQ on docker with the command below.
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.12-management
