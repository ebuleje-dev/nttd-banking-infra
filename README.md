# nttd-banking-infra

### Compose Sonarqube
```
docker-compose -f sonar/docker-compose-sonarqube.yml up -d
docker-compose -f sonar/docker-compose-sonarqube.yml down
```

### Compose - Developer
```
docker compose -f docker-compose.dev.yml up -d
docker compose -f docker-compose.dev.yml down
```

### Compose - nttd
```
docker compose -f docker-compose.yml up -d
docker compose -f docker-compose.yml down
```