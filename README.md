# Reverse Proxy

## Project Description

This project provides a reverse proxy configuration based on the `valian/docker-nginx-auto-ssl` Docker image.  
It allows forwarding client subdomain requests to multiple Docker containers running either on the local host or within Docker networks.  

**Features:**  
- Automatic SSL certificate issuance and renewal.

**Note:**  
- The included `compose.yml` is designed for use within Docker networking. It expects that all Docker apps are running in the **same network** as the reverse proxy for proper request forwarding. 
- The `compose-host.yml` is intended for **localhost forwarding** and does **not** require all apps to be in the same network.

## Usage

For detailed information and configuration options, see the official documentation:  
[https://hub.docker.com/r/valian/docker-nginx-auto-ssl](https://hub.docker.com/r/valian/docker-nginx-auto-ssl)

## License

This project is licensed under the MIT License.
