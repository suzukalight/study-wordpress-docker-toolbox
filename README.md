# study-wordpress-docker-toolbox

for Windows 10 Home

## Setup Docker Toolbox

1. Download `Docker Toolbox`  
https://docs.docker.com/toolbox/toolbox_install_windows/

2. Setup Docker Toolbox
3. Open `Docker QuickStart Terminal`
4. Wait for setup
5. Setup will be completed if the following message is displayed

```
docker is configured to use the default machine with IP 192.168.99.100
For help getting started, check out the docs at https://docs.docker.com


Start interactive shell

$
```

## Run wordpress

```
docker-compose up -d
```

Now you can see your WordPress site on http://192.168.99.100:8080

Or your IP address was;

```
$ docker-machine env

export DOCKER_HOST="tcp://192.168.99.100:2376"
```

## References

- https://hub.docker.com/_/wordpress/
- https://qiita.com/azu369yu/items/e9415024e84c86a9e577
