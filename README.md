# SETUP

### Clone git sources
```
fortune-workspace/fortune-api
fortune-workspace/bit-mini-games
fortune-workspace/bit-partner-mini-games
fortune-workspace/game-microservice
...
```

### Docker Credentials
```
User: 1bitdev
Token: dckr_pat_nnp86UhOcIGdD2un94AzKbjm27s
```

### Start common services
```shell
docker compose -f docker-compose.common.yml up -d
```

### Start api services
```shell
docker compose up -d
```
