---
title: Setup
description: Recipe Description
hidden: false
recipe:
  color: '#018FF4'
  icon: 🦉
---
```shell Shell
helm repo add influxdata https://helm.influxdata.com/
helm install myinfluxdb influxdata/influxdb2
```

```json Response Example
{"success":true}
```

# Install minkube

<!-- shell@ -->

https://minikube.sigs.k8s.io/docs/start/

# Install InfluxDB

<!-- shell@ -->

https://docs.influxdata.com/platform/install-and-deploy/deploying/kubernetes/