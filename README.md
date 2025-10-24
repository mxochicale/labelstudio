# Labelstudio


## References

* https://medium.com/@an.ehteesham/label-studio-yolov8-prelabeling-guide-6fa3d7048219




## Docker commands
Clean up the container images:
```
docker system prune -f --volumes
docker rmi --force <ID>
docker images --format '{{.Repository}}:{{.Tag}}' | grep '^vsc-holohub' | xargs -r docker rmi
```

```
docker images
docker ps
docker attach <ID>
docker stop <ID>
docker rename keen_einstein mycontainer
docker rmi --force <ID>

docker stop $(docker ps -a -q)
docker system prune -f --volumes #clean unused systems
```




### TO REMOVE


```bash
docker compose up #Attached Initial setup, debugging, seeing real-time logs
#docker compose up -d #Detached Production use, running in background
docker compose down
docker compose stop
```



