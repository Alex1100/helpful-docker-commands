# DOCKER COMMANDS TO REMEMBER

```diff
+ CONTAINERS
```

```bash
docker container run image_name
```
- Arguments taken in with this command include:
- -d (for detaching the container) 
- --name some_alias 
- -p port_number i.e 80:80 / 8080:80 / etc...
- -e environment variables
- image name to run / or pull if not found locally then to be ran. i.e httpd

```bash
docker container ps or docker container ls
```
- Arguments takin in with this command include:
- -a to list all containers both stopped and running

```bash
docker container top image_name or container id
```
- Lets us look at the processes running within a specific container

```bash
docker container stop image_name or container_id
```
- stops a live container and prepares it to possibly be removed

```bash
docker container remove image_name or container_id
```
- Removes a container from the network or machine

```diff
+ IMAGES
```

```bash
docker image ls
```
- List out all images found on local machine
