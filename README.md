Bare-Metal Observability Lab
A minimal, Linux-first observability stack built without containers or Kubernetes.
Goal
Design and operate a lightweight, on-prem monitoring system using systemd-managed services and single-binary deployments.

Stack

VictoriaMetrics (time-series database)
Grafana (dashboards)
Alertmanager (alert routing)
node_exporter (system metrics)
systemd (service management)

Design Principles

Minimal and understandable
Close to the hardware
No Docker, no Kubernetes
Single-binary deployments
Explicit service management via systemd

Features (In Progress)

Service deployment using custom systemd units
Metrics scraping and storage
Alert rules for CPU, memory, and service failures
Failure simulation and validation
Operational runbooks

Planned Enhancements

Reverse proxy with TLS
Log ingestion pipeline
Backup automation
Cross-host service replication
