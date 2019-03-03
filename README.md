# DOCKER COMMANDS TO REMEMBER

<h1>CONTAINERS</h1>

```bash
docker container start -ai <container_name> || <container_id>
```
# <span></span>
- -ai <container_name> || <conainer_id>, flag is needed to start an existing container

```bash
docker container run image_name
```
# <span></span>
- Arguments taken in with this command include:
- -it provides an interactive shell and psuedo-TTY
- -d (for detaching the container) 
- --name some_alias 
- -p port_number i.e 80:80 / 8080:80 / etc...
- -e environment variables
- image name to run / or pull if not found locally then to be ran. i.e httpd
- flags after the image name include:
    1. bash -> if run with -it, it will give you a terminal inside the running container
```bash
docker container ps || docker container ls
```
# <span></span>
- Arguments takin in with this command include:
- -a to list all containers both stopped and running

```bash
docker container top image_name || container id
```
# <span></span>
- Lets us look at the processes running within a specific container

```bash
docker container stop image_name || container_id
```
# <span></span>
- stops a live container and prepares it to possibly be removed

```bash
docker container remove image_name || container_id
```
# <span></span>
- Removes a container from the network or machine

```bash
docker container inspect container_name || container_id
```
# <span></span>
- Show metadata about the container (startup, config, volumes, networking, etc...)

```bash
docker container stats
```
# <span></span>
- Shows live performance data for all containers

```bash
docker container stats container_name || container_id
```
#<span></span>
- Show live performance for a specific container


<h1>IMAGES</h1>

```bash
docker image ls
```
# <span></span>
- List out all images found on local machine
