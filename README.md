# Monitoring Sample
Sample code for monitoring, grafana and prometheus

<img width=80% src="https://user-images.githubusercontent.com/1712116/84417854-32a19480-ac51-11ea-9f53-53a28a9e5eb1.png"/>

# Architecture
![oppai_monitoring](https://user-images.githubusercontent.com/1712116/99880096-a01c0d00-2c54-11eb-8059-165233567a01.png)

# How to use

```
$ docker-compose up -d
# Access to http://localhost:3000  id:password = admin:admin
```

# Applications
## Middleware
- Grafana 7.0.3
- Prometheus 2.18.1
- Alertmanager 0.20.0

## Exporter
- node_exporter
- redis_exporter
- mysql_exporter

## Dashboard
- [OS Metrics](https://grafana.com/grafana/dashboards/405)
- [Redis/RedisCluster](https://grafana.com/grafana/dashboards/763)
- MySQL/InnoDB
