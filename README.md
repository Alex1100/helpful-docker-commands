DOCKER COMMANDS TO REMEMBER

## CONTAINERS

# <code>docker container run <i>image_name</i></code>
- Arguments taken in with this command include:
- -d (for detaching the container) 
- --name some_alias 
- -p port_number i.e 80:80 / 8080:80 / etc...
- -e environment variables
- image name to run / or pull if not found locally then to be ran. i.e httpd

# <code>docker container ps</code> or <code>docker container ls</code>
- Arguemtns takin in with this command include:
- -a to list all containers both stopped and running

# <code>docker container top <i>image_name or container id</i></code>
- Lets us look at the processes running within a specific container

# <code>docker container stop <i>image_name or container_id</i></code>
- stops a live container and prepares it to possibly be removed

# <code>docker container remove <i>image_name or container_id</i></code>
- Removes a container from the network or machine

## IMAGES

# <code>docker image ls</code>
- List out all images found on local machine
