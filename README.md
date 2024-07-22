# My homelab repo

## General idea/concept
Upload scripts I will be using on my local server, part of my [100 days of code challenge](https://akirapearl.github.io/jekyll_blog/) 

## Diagram
![Diagram for a local server Ansible deployment](https://raw.githubusercontent.com/Akirapearl/homelab/main/images/server.png)


## Configuration Client & Server side
- Install Ansible locally (not a server), wipe server with fresh OS installation. - :white_check_mark: CHECK
- Define working directory and Ansible's inventory.
- Configure SSH keys. - :white_check_mark: CHECK


### Automation Tasks
- Check connectivity via ansible all -m ping.
- Secure ssh access
- Update packages

## Deploy - Docker compose
- Photoprism
- NextCloud
- NGINX Proxy Manager
- Jenkins (Java/Golang compiling)

### Potential upgrades

 - Landing/home page. [Example for a homepage](https://github.com/daledavies/jump)
 - System/Network Monitoring. [Dashdot](https://github.com/MauriceNino/dashdot) / [Grafana](https://grafana.com/) 

