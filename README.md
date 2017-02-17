# MCHostPanel-docker

```docker run --detach \
    --env 'VIRTUAL_HOST=<Your HOST>' \
    --name mcpanel \
    --restart always \
    --publish 80:80 \
    --volume <Your MC Path>:/data \
    killergoldfischmchostpane```
    
The data directory should contain a craftbukkit.jar file.
The new User should get `'/data'` as home.
