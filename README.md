# Docker-compose:
# InfluxDB
# + Grafana 
# + Telegraf

Run:
```
docker-compose up -d
```
Show logs:
```
docker-compose logs -f
```
Stop it:
```
docker-compose stop
```
Start it:
```
docker compose start
```
Grafana:
```
http://localhost:3000
user: admin  password: admin
```
Config. Grafana:
HTTP
```
INFLUXDB
URL: http://influxdb:8086
Server (default)
```
InfluxDB Details
```
Database: telegraf
User: root
```