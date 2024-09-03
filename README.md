[![Datalayer](https://assets.datalayer.tech/datalayer-25.svg)](https://datalayer.io)

# Ξ Datalayer Grafana Dashboards

This repository contains the dashboard definitions for the Datalayer Observer service. Read more on [Datalayer Tech](https://datalayer.tech/docs/build/kubernetes/services/system/observer). We are using the following tools to create the dashboards:

- `OpenTelemetry Collector`:
    - As deployment to proxy metrics and traces from Datalayer services to Prometheus and Tempo.
    - As daemonset to parse pod log files and send them to Loki.
- `Prometheus`: To gather metrics.
- `Tempo`: To gather traces.
- `Loki`: To gather logs.
- `AlertManager`: To manage alerts.
- `Grafana`: To visualize and analyze the telemetry.

### Services

<img src="https://datalayer-assets.s3.amazonaws.com/observer/observer-services.png" />

### Overall View

<img src="https://datalayer-assets.s3.amazonaws.com/observer/observer-overall-view.png" />

### Detailed View

<img src="https://datalayer-assets.s3.amazonaws.com/observer/observer-detailed-view.png" />
