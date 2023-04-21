# varnish-chart

Helm chart for Varnish Cache

# Working with varnish exporter for k8s

## Quick Start

## Install the chart

To install the chart with Helm v3 as _my-release_ deployment:

```bash
helm upgrade --install varnish ../varnish --create-namespace --namespace varnish -f values.yaml
```

## Upgrade the chart

```bash
helm upgrade varnish ../varnish -n varnish -f values.yaml
```