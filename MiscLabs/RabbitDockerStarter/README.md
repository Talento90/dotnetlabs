# RabbitMQ on Docker Starter

```Docker
# interactively
docker run --rm -it --hostname my-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management

# detached
docker run --rm -d --hostname my-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management
```

## Screen Recording

A basic pub/sub model with one message producer and two consumers.

![rabbitmq starter](./rabbitmq-starter.gif)
