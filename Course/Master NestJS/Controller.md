# Controller

![image-20230529230610815](/Users/linling/Library/Application Support/typora-user-images/image-20230529230610815.png)



Controllers are responsible for handling incoming **requests** and returning **responses** to the client.

The **routing** mechanism controls which controller receives which requests. Frequently, each controller has more than one route, and different routes can perform different actions.

In order to create a basic controller, we use classes and **decorators**. Decorators associate classes with required metadata and enable Nest to create a routing map (tie requests to the corresponding controllers).

[CRUD generator]

## Routing