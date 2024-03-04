# SETUP

### Clone git sources
```
cd fortune-workspace
git clone git@github.com:1Bit-Software-Development-Corp/lottery-api.git
...
```

### Docker Credentials
```
User: 1bitdev
Token: dckr_pat_nnp86UhOcIGdD2un94AzKbjm27s
```

### Create docker network
```shell
docker network create share-network
```

### Start common services
```shell
docker compose -f docker-compose.common.yml up -d
```

### Start api services
```shell
docker compose up -d
```
