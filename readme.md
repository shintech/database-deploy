## shintech/database_deploy

### Synopsis

Deployment for shintech/database

### Usage

#### create network

If network is not already created...

    docker network create -d bridge --subnet 192.168.0.0/24 --gateway 192.168.0.1 docker_network
    
#### pull and start

    docker-compose pull
    
    docker-compose up -d