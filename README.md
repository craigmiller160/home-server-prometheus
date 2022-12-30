# Home Server Prometheus

Integrates Prometheus monitoring and the Grafana UI into the cluster.

## Repository

```bash
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo add prod_nexus https://nexus-craigmiller160.ddns.net/repository/helm-private
```

## Environment Variables

The following shell environment variables must be present on the machine in order to properly deploy this chart:

```bash
The admin password for logging into Grafana
GRAFANA_ADMIN_PASSWORD=######
```