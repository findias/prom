## Home Monitoring with Prometheus


### Monitoring consists of 3 container:

- Prometheus
- NodeExporter
- Grafana


### Install

Create folder:
```
mkdir -p /some/path/
```
Go to folder:
```
cd /some/path
````
Clone repo:
```
git clone https://github.com/findias/prom .
```
Build image and sart container
```
docker compose up -d
```

open Grafana on localhost:3000
open Prometheus on localhost:9090
