

---

# DevOps Monitoring & Logging Platform

## Project Purpose

This project builds a **Linux monitoring and logging platform** using DevOps tools.
It collects system metrics and logs from a Linux server and visualizes them through Grafana dashboards.

The system helps administrators monitor:

* CPU usage
* Memory usage
* Disk usage
* Network traffic
* System logs

---

## Project Structure

```
devops-monitoring-platform
│
├── docker-compose.yml
├── prometheus/
│   └── prometheus.yml
├── promtail/
│   └── promtail.yml
├── loki/
│   └── config.yml
├── alertmanager/
│   └── alertmanager.yml
└── README.md
```

---

## Features

* Linux system monitoring
* Real-time metrics collection
* Centralized log aggregation
* Grafana monitoring dashboards
* Docker-based deployment
* Alert management system

Tools used:

* Linux
* Docker
* Prometheus
* Node Exporter
* Grafana
* Loki
* Promtail
* Alertmanager

---

## Commands

### Start monitoring platform

```bash
docker-compose up -d
```

### Stop monitoring platform

```bash
docker-compose down
```

### Check running containers

```bash
docker ps
```

### View container logs

```bash
docker logs grafana
```

### Restart monitoring stack

```bash
docker-compose restart
```

---

## Access Services

| Service      | URL                                            |
| ------------ | ---------------------------------------------- |
| Grafana      | [http://localhost:3001](http://localhost:3001) |
| Prometheus   | [http://localhost:9090](http://localhost:9090) |
| Alertmanager | [http://localhost:9093](http://localhost:9093) |

Grafana login:

```
username: admin
password: admin
```

