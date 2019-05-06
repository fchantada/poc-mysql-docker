# Docker MYSQL Replication - Master/Master

## Prerequisites

+ Vagrant 2.2.4 or higher.
+ Hypervisor: 
    + VirtualBox 6.0 or higher.
    + Hyper-V 10 or higher.
+ Mysql client (example: MySQL Workbench)


## How to use?

For start Sandbox
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

For destroy Sandbox

```
  $ vagrant destroy
```

## Another Vagrant Commands

Stop Sandbox
```
  $ vagrant halt
```
Connect to Sandbox via ssh
```
  $ vagrant ssh
```

Reconfigure Sandbox after a source code change
```
  $ vagrant provision
```

Reload Sandbox
```
  $ vagrant reload
```
