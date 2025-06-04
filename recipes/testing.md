---
title: Testing
description: Recipe Description
hidden: true
recipe:
  color: '#018FF4'
  icon: 🦉
---
```shell Shell
docker build -t augie/arris_cable_modem_stats:debug -f arris-stats-debug-dockerfile .
docker run -d augie/arris_cable_modem_stats:debug
docker build -t augie/sb8200_spoof -f ./nginx-dockerfile .
docker run -d -p 8080:80 augie/sb8200_spoof
```

```json Response Example
{"success":true}
```

# Build docker image

<!-- shell@1-2 -->

Use the debug configuration to build an image with debugging enabled

# Build docker image

<!-- shell@3-4 -->

Spoof the SB8200 connection status page for testing