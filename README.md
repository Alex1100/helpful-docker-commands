DOCKER COMMANDS TO REMEMBER

## CONTAINERS

# <code>docker container run <i>image_name</i></code>
<p>Arguments taken in with this command include:</p>
- -d (for detaching the container) 
- --name some_alias 
- -p port_number i.e 80:80 / 8080:80 / etc...
- -e environment variables
- image name to run / or pull if not found locally then to be ran. i.e httpd

# <code>docker container ps</code> or <code>docker container ls</code>
<p>Arguemtns takin in with this command include:</p>
- -a to list all containers both stopped and running

# <code>docker container stop <i>image_name or container_id</i></code>

# <code>docker container top <i>image_name or container id</i></code>
<p>Lets us look at the processes running within a specific container</p>


## IMAGES

# <code>docker image ls</code>
<p>List out all images found on local machine</p>
