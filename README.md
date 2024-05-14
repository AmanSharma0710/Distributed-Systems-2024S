# Distributed-Systems-2024S

This repository is to maintain code for the assignments given in Distributed Systems course, 2024 Spring. Each assignment is in a separate folder with its own README file explaining the problem statement and the solution. 

### Instructions to run the code
Follow the instructions in the respective README files. 

### Cloning the repository
To access individual assignments, clone the repository of the respective assignment. \
To clone the entire repository, use the following command:
```bash
git clone --recurse-submodules <repository-url>
```

## Assignment-1: Customizable Load Balancer

The first assignment is to implement a customizable load balancer. The load balancer should be able to manage a set of N web server containers and distribute the incoming requests among them. The load balancer should be able to add and remove server instances when prompted by the user. The load balancer should also be able to route requests to the appropriate server based on a consistent hashing algorithm. The code can be found in the `Assignment-1` folder.

## Assignment-2: Implementing a Scalable Database with Sharding

The second assignment is to implement a scalable database with sharding. The requests are routed to the appropriate shard, and there are multiple replicas of the same shard for redundancy and parallelism. The code can be found in the `Assignment-2` folder.

## Assignment-3: Implementing a WAL Replicated Database with Sharding

The third assignment is to implement a Write-Ahead Logging (WAL) Replicated Database with Sharding. The database should be able to replicate logs across multiple servers and maintain consistency in the presence of failures. The code can be found in the `Assignment-3` folder.