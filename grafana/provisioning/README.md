# Grafana Provisioning
See documentation: https://grafana.com/docs/grafana/latest/administration/provisioning/

## Datasources
One datasource is defined: `Prometheus`, on port `9090`. -> `prometheus:9090` in docker.

## Dashboards
Please add following dashboards in grafana UI:
- NodeExporter: https://grafana.com/grafana/dashboards/1860
- Docker/cAdvisor: https://grafana.com/grafana/dashboards/893
- Traefik: https://grafana.com/grafana/dashboards/11462
- Blackbox: https://grafana.com/grafana/dashboards/7587