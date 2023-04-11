Create networks

```bash
docker network create \
  --subnet=172.20.0.0/16 \
  --gateway=172.20.0.1 \
  nktc_stu


```

Create volume

```bash
docker volume create postgres_data
docker volume create pgadmin_dat
docker volume create minio_storag
docker volume create jenkins_hom

```

Load the tunnel token into the environment variable on your server by executing:

```sh
export TUNNEL_TUKEN=xxxxx
```
