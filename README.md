# Warm Tea and Honest Monitoring

This repository contains the monitoring infrastructure for the "Warm Tea and Honest" API server. It sets up a monitoring stack using Prometheus and Grafana to scrape and visualize metrics.

## Overview

The setup includes:
- **Prometheus**: Configured to scrape metrics from the API server at `84.235.166.193:8080` via the `/actuator/prometheus` endpoint.
- **Grafana**: Pre-configured with Prometheus as the default data source for visualization.

## Getting Started

To start the monitoring stack, ensure you have Docker and Docker Compose installed, then run:

```bash
docker-compose up -d
```

- **Prometheus UI**: [http://141.148.231.40:9090](http://141.148.231.40:9090)
- **Grafana UI**: [http://141.148.231.40:3000](http://141.148.231.40:3000)