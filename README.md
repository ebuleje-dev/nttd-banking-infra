# nttd-banking-infra


### Levantar SonarQube en segundo plano
```
docker-compose -f sonar/docker-compose-sonarqube.yml up -d
```

### Detener docker compose sonar
```
docker-compose -f sonar/docker-compose-sonarqube.yml down
```

### Levantar docker compose kafka
```
docker compose -f kafka/docker-compose-kafka.yml up -d
```

### Detener docker compose kafka
```
docker compose -f kafka/docker-compose-kafka.yml down
```