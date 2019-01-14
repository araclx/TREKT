# TREKT

A product designed for traders that will allow them to additional monetize their stock movements and optimize their work through functions such as dynamic risk management, creating dynamic technical analysis or suggesting transactions through artificial intelligence.


## Install

The simplest way to set up a test instance of TREKT is to use ready Docker images from [REKTRA Network Docker Hub](https://hub.docker.com/u/rektranetwork).

You can use [deployments/docker-compose.yml](https://github.com/rektra-network/TREKT/blob/master/deployments/docker-compose.yml) as an example of TREKT-network structure:

    git clone https://github.com/rektra-network/TREKT.git
    cd TREKT
    docker-compose -f deployments/docker-compose.yml up -d

[TREKT API](https://github.com/rektra-network/TREKT/wiki/Terminal-API) endpoint will now be reachable at ws://localhost:8080.

## API

[Terminal API](https://github.com/rektra-network/TREKT/wiki/Terminal-API).


## See also

[Go-part](https://github.com/rektra-network/trekt-go) of TREKT project.
