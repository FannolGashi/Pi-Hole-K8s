# Create you own Pi-Hole container in K8s.

## Installation
Download and install [Docker Desktop](https://www.docker.com/products/docker-desktop/) and enable K8s.

Create a container with Pi-Hole image.
```bash
kubectl apply -f pihole.yml
```
## Usage
Since, we have exposed port TCP 80, then your Pi-Hole deployment can be accessed via http://localhost from your browser.