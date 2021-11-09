# seatable

https://manual.seatable.io/docker/Developer-Edition/Deploy%20SeaTable-DE%20with%20Docker/

```
docker-compose up seatable

# Start SeaTable service.
docker exec -d seatable /shared/seatable/scripts/seatable.sh start

# Create an admin account.
docker exec -it seatable /shared/seatable/scripts/seatable.sh superuser  
```
