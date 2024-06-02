# Subscriber with Message Broker

## Knowledge Check
1. What is `amqp`?

    AMQP or Advanced Message Queueing Protocol is a standard application layer protocol that allows client applications to communicate with servers and interact. AMQP also defines network layer protocols and a _high-level architecture_ for _message brokers_.

2. What it means? `guest:guest@localhost:5672`, what is the first `guest`, and what is the second `guest`, and what is `localhost:5672` is for?
    - The first `guest` is _username_ while the second `guest` is _password_. In this case, `guest:guest` means the _username_ and _password_ are guest.
    - `localhost:5672` means the server is running on the client machine with port 5672 which is the default port for AMQP.
