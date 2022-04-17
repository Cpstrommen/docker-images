# docker-images
### A collection of docker and docker-compose files to speed up deployment

## Currently Included Applications
 
- Homebridge (third party hardware support for Apple Homekit)
- Homer (a landing page for locally hosted applications)
- PiHole (local DNS and adblocking server)

### Integration of Multiple Docker Network Services

- For a more comprehensive guide to setting up local network services using Docker containers, check out my [Network Pi Project](https://github.com/Cpstrommen/network-pi)
- As for interfacing with a local network, be mindful of the docker network connected (host, bridge, etc.) and the ports assigned in order to properly route network between dependant services

## Contribution Guidelines
Submit pull requests divided by application and including each working `docker-compose.yml` file. All submissions **must** be compatible with arm64 architectures for our Raspberry Pi and M1 chip friends. 
