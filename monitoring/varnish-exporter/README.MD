# varnish exporter k8s

Varnish exporter with exporter version 1.6.1 get from git@github.com:jonnenauha/prometheus_varnish_exporter.git

## Build

```bash
docker build -t youorg/image_name:version .
```

## set you imege values.yaml

```yaml
prometheus:
  enabled: true
  image:
    repository:  chernyenkocomua/varnish-prometheus-exporter
    tag: 1.6.1
```

