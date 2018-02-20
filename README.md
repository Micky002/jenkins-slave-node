Jenkins jnlp slave with node included

## How to use

Start the container

    docker run wemicky/jenkins-slave-node:latest -url http://jenkins-server:port <secret> <agent name>

## Options

To use more custom options see the "base" image [node](https://hub.docker.com/_/node/).
