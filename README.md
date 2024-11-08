# grafana
Everyone needs a grafana

# Procs

## Reset log data ingested
```
docker compose down
docker volume rm grafana_loki_storage
docker compose up -d --force-recreate
docker compose logs -f
```
