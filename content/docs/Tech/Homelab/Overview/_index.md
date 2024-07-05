---
weight: 1
title: "Overview"
---

# Overview
Here's a short overview of my homelab environment, starting with Docker containers, this will be slowly updated.


## Services

### Docker

I have Docker running on multiple hosts, primarily for testing different applications and some monitor tools

#### Uptime Kuma
Running in Docker container, monitors hosts uptime and alerts when they are unreachable, also some modified script monitoring

#### Jenkins
For CI/CD

#### HashiCorp Vault
Storing secrets

#### Grafana
Used to display data collected in InfluxDB and Prometheus

#### InfluxDB
Time-series Database, using Telegraf to collect metrics from various devices


#### Prometheus
Used to collect metrics from various devices/services


# Proxmox cluster
I have two machines that runs Proxmox in a cluster, contains 3 VM's for various projects

#### Pi-Hole
I run Pi-Hole as a VM

