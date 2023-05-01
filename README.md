Create networks

```bash
docker network create \
  --subnet=172.20.0.0/16 \
  --gateway=172.20.0.1 \
  nktc_stu


```

Load the tunnel token into the environment variable on your server by executing:

```sh
export TUNNEL_TOKEN=xxxxx
```
