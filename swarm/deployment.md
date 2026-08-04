# Docker Swarm Deployment


## Cluster Architecture

Manager Node:
- Cluster management
- Service orchestration


Worker Nodes:
- Application execution


Topology:

Manager
 |
 |--- Worker 1
 |
 |--- Worker 2


## Deployment

Initialize swarm:

docker swarm init


Deploy stack:

docker stack deploy -c docker-stack.yml knowhub


Check services:

docker service ls
