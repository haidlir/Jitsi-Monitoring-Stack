In case you find this error
```
ERROR: Network jitsi-monitoring-stack declared as external, but could not be found. Please create the network manually using `docker network create jitsi-monitoring-stack` and try again.
```
You can fix it by send this command
```
docker network create jitsi-monitoring-stack
```