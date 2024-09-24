# CONTRIBUTING

## How to run Dockerfile locally

```
docker compose up -d --build

#docker run -d --name=pappa -p 5002:5002 -w /app -v "$(pwd):/app" pappa-api
#docker run -d --name=pappa-secplus -p 5002:5002 -w /app -v "$(pwd):/app" #pappa-api-secplus
docker logs -f pappa

```

#Setup reminders:
```
chmod +x ./init/init-db.sh
#create network:
docker network create pappa_network
````