# Transfer.sh service

This is just a swarm stack that runs [transfer.sh](https://github.com/dutchcoders/transfer.sh/).  To deploy it you need to do :

```sh
export TRAEFIK_BACKEND=transfersh
export TRAEFIK_HOSTNAME=host.domain.com
docker stack deploy -c stack.yml transfersh
```
