# Monitoring-Pet-Project
Monitoring stack example using Prometheus, Alertmanager, Grafana, and Node Exporter with custom alerting rules and webhook integration. Docker Compose setup for local practice and training.

The `node-exporter` service is configured to mount the host's `/proc`, `/sys` and root filesystem so that metrics from the Docker host itself are collected.
