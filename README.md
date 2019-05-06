# Docker MYSQL Replication - Master/Master

## Prerequisites

+ Vagrant 2.2.4 or highter.
+ VirtualBox 6.0 or highter.


## How to use?

For start stack
```
  $ vagrant up
```

Connection String for connect to MYSQL Node 1 (default parameters): 
+ host: 127.0.0.1 (localhost)
+ port: 13306
+ user: example_user 
+ pass: 123456

Connection String for connect to MYSQL Node 2 (default parameters): 
+ host: 127.0.0.1 (localhost)
+ port: 23306
+ user: example_user 
+ pass: 123456

For down stack

```
  $ vagrant down
```