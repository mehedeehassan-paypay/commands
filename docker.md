
### DELETE ALL IMAGES
```
docker rmi -f $(docker images -aq)
```
```
docker kill $(docker ps -q)
docker_clean_ps
docker rmi $(docker images -a -q)
```


### COLIMA
```
colima start
docker compose up
```
