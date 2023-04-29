## Home Monitoring with Prometheus


### Monitoring consists of 3 container:

- Prometheus
- NodeExporter
- Grafana


### Install

Create folder:
``` bash
mkdir -p /some/path/
```
Go to folder:
``` bash
cd /some/path
``` bash
Clone repo:
``` bash
git clone https://github.com/findias/prom .
```
Build image and sart container
``` bash
docker compose up -d
```

Services is available:

- open Grafana on http://localhost:3000
- open Prometheus on http://localhost:9090
