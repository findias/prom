## Home Monitoring with Prometheus


### Monitoring consists of 3 container:

- Prometheus
- NodeExporter
- Grafana


### Install 
```
mkdir -p /some/path/
cd /some/path
git clone https://github.com/findias/prom .
docker compose up -d
```
open Grafana on localhost:3000
open Prometheus on localhost:9090
